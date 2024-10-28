[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ETUnPycw)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15640237)
# OI 244 Practical Assignment Three
- Student Number: 23779411
- Practical Group: 4
- Total Marks Available: 50

## Assignment Instructions

1. Before starting, wait a moment and then perform a `git pull` in case GitHub Classroom made an extra commit after you started your Codespace.

2. Update this `README.md` file to include your student number and practical group on lines 2 and 3.

3. [5] This week's assignment focuses on CSS, but in order to style your content, you need content. To this end, create an `index.html` file and choose a Wikipedia article to use for content. Copy the title and first paragraph (or paragraphs, above the Table of Contents) into your `index.html` page and then format it with HTML tags so that it looks as close to the original as you can get it. Be sure to include a comment with a link/citation to the source. You need not replicate any of the links.

4. [2] Create a CSS stylesheet with the name `style.css` and link to it as an external stylesheet in the source of your document. To do this, insert the below tag into the `head` of your document:

    ```html
    <link rel="stylesheet" href="/style.css">
    ```

    Notice the similarities to linking the stylesheet and regular links and images.

5. [10] Our objective is to make our page look a little like Wikipedia. To do this, we will need to write styles that bring the styling a little closer. You should write styles in the `style.css` file to try to mimic this design.

    To do this, it is suggested you start by writing a style that changes the whole document. You _could_ do this for the `html` element, but it is more common to do this for the _body_ element.

    Write a selector per the below snippet that will apply to the entire `body` element, and then apply some CSS properties to make it look more like Wikipedia.

    ```css
    body {
        // Your properties go here
    }
    ```

    w

6. [5] Once you've done this, make some changes to the `h1` element styling as well. Consider making it a different colour, weight, or size. You don't need to stick with Wikipedia design too closely.

7. [5] Now that you've done all of that, make sure that your page looks the way you'd like, create a second page on a related article from Wikipedia, and repeat the process in question 3 for the second page. Then link the same stylesheet as you did before and watch the magic happen. One stylesheet for the whole site makes for consistent design.

8. [20] Make use of the CSS resources linked on SUNLearn and make your stylesheet more interesting. You can play with alignment, colour, sizes, etc. Consider the principles of good design that you learned about in Socio-Informatics 214. Add at least two additional rules (selector, property sets), so that there are at least four in total. Make sure, across all your rules, that you set at least 10 properties.

9. [3] Do you need to be reminded to Save, Add, Commit, Push?
