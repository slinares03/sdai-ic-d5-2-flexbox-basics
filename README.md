## Solo - Creating a Flexible Image Gallery 💪

**Description:**
Students will independently create a flexible image gallery that adapts to different screen sizes using flexbox.

**Instructions:**
Visit the [Flexbox Playground](https://animated-broccoli-qk8y6p8.pages.github.io/) to understand how each flexbox property works. This interactive tool allows you to play with various flexbox properties and see the results live.

### Flexbox Properties Guide

| Property          | Values                                | Description                                                                 |
|-------------------|---------------------------------------|-----------------------------------------------------------------------------|
| flex-direction    | row, row-reverse, column, column-reverse | Defines the direction in which the flex items are placed in the container.  |
| flex-wrap         | nowrap, wrap, wrap-reverse            | Controls whether the flex items should wrap onto multiple lines or stay in a single line. |
| justify-content   | flex-start, flex-end, center, space-between, space-around | Aligns flex items along the main axis of the container.                     |
| align-items       | flex-start, flex-end, center, baseline, stretch | Aligns flex items along the cross axis of the container.                     |
| align-content     | flex-start, flex-end, center, space-between, space-around, stretch | Aligns flex lines when there is extra space in the cross axis.              |
| order             | <integer>                             | Controls the order in which flex items appear in the flex container.         |

### ToDo list ✅

1. **Introduction:**
    - [ ] Understand the requirements of a flexible image gallery.

2. **Step-by-Step Walkthrough:**
    - [ ] **Task 1:** Create the HTML structure.
        - Add a `<section>` container with a class of `gallery`.
        - Add at least six `<img>` elements. Images have been provided in the `assets/images` folder.
    - [ ] **Task 2:** Style the image gallery using flexbox.
        - Set `display: flex;` on the `gallery` class.
        - Use `flex-wrap` to wrap the images onto multiple lines.
        - Use `justify-content` to space the images evenly.
        - Use `align-items` to center the images vertically.
    - [ ] **Task 3:** Style the images.
        - Set a fixed width and height for the images to ensure they are the same size. Starting with something like this can let you specify only images in the gallery:
        ```css 
        .gallery img {
            width: /* set a value that you feel looks good */;
            height: /* set a value that you feel looks good */;
        }
        ```
        - Use the `object-fit` property with the value `cover` to ensure the images look great at the specified size.
        - **Note:** This is a common technique for making galleries look great with minimal code. 


3. **Review:**
    - [ ] View the updated work, ensure all changes are applied correctly, and discuss further improvements.

### Congratulations 🎉

You have successfully completed the exercise on creating a flexible image gallery using flexbox! Great job! You've learned how to:

- Structure HTML for an image gallery.
- Use flexbox properties to create responsive layouts.
- Apply styles to ensure your gallery images are aligned and distributed correctly.

Keep experimenting with different flexbox properties to enhance your layouts and become a flexbox pro!
