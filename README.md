## Solo - Creating a Flexible Image Gallery 💪
**Description:**
Students will independently create a flexible image gallery that adapts to different screen sizes using flexbox.

### Prepare Your Workspace
1. [ ] First, stop any other Codespaces you have running to conserve core hours.

## Forking Repositories
When you fork a repo, there is a box checked by default to only copy the main branch. You will want to uncheck this box so that you get all the branches you need. 

If you forget to uncheck that box, you can still get access to the other branches you need. You'll need to follow the instructions from GitHub [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch), taking special note of step 5 when you reach it.

## Branch Management
These activities use several branches. After watching your instructor's initial demo, you'll need to use two branches in order. 

First, you'll need to use the `together` branch to try an activity alongside your instructor. This may be very similar to the demo you saw, but you'll get to practice these skills, too.
Next, you'll use the `solo` branch to push yourself and learn more. Getting hands on like this teaches you a lot, but you can still ask your AI and your instructor for help.

You can switch branches by using this command:

`git checkout branch-name`

Examples:

```
git checkout together
```

```
git checkout solo
```

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
**Attention**: When you complete a task, put an `x` in the middle of the brackets to mark it off your ToDo list.

1. **Introduction:**
    - [ ] Understand the requirements of a flexible image gallery. You might notice the images are also optimized to be smaller than images we've used in prior lessons, which comes with costs and benefits, but is generally a best practice whenever you don't need larger, higher quality images.

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
        - Set a fixed width and height for the images to ensure they are the same size, and craft two rows with 3-5 images per row. **Tip:** Starting with something like this can let you specify only images in the gallery:
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