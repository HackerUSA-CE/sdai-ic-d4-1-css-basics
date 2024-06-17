# Try it Together | Basics of CSS Styling

## Forking Repositories
When you fork a repo, there is a box checked by default to only copy the main branch. You will want to uncheck this box so that you get all the branches you need at once. 

If you forget to uncheck that box, you can still get access to the other branches you need. You'll need to follow the instructions from GitHub [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch), taking special note of step 5 when you reach it.

## Branch Management
These activities use several branches. After watching your instructor's initial demo, you'll need to use two branches in order. 

First, you'll need to use the `together` branch to try an activity alongside your instructor. This may seem very similar to the demo you saw, but this time you're getting hands on practice with these skills. 

Next, you'll use the `solo` branch to push yourself and learn more. 

You can switch branches by using this command:

`git checkout branch-name`

Examples:

```
git checkout together
```

```
git checkout solo
```

## ToDo list ✅
**Attention**: When you complete a task, put an `x` in the middle of the brackets to mark it off your ToDo list.

### Prepare Your Workspace

1. [ ] First, stop any other Codespaces you have running to conserve core hours.

## Create Your First CSS File
2. [ ] Perform these steps alongside your instructor to create your first CSS file.
    - Right-click on your explorer on the left.
    - Click New File.
    - Name it `styles.css`.
    - Click on your HTML file to return to viewing your HTML code.

## Link Your CSS File to Your HTML File
3. [ ] With your instructor's guidance, successfully link to your CSS file.
    - In your HTML file, create a `<link>` element within the `<head>` element.
    - Give that `<link>` element this `rel` attribute: `rel="stylesheet"`.
    - Then, give it this `href` attribute: `href="styles.css"`.
    - Note that this must be the name of the CSS file we created.

    Now, your head element should look like this:

    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Simple Web Page</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    ```

## Change Paragraph Text Color
Earlier, we saw how we could change the color of all paragraph text to blue and set a light gray background, but it didn’t look fantastic. Let’s try to improve our text colors this time.

 4. [ ] Write your first CSS inside your `styles.css` file.
    - Return to your CSS file by clicking on `styles.css` in your explorer menu on the left.
    - In here, you can type any CSS code you want applied. Remember, we must start with a selector, so start by choosing all paragraphs by typing `p`.
    - Then, open your declaration block by typing `{}`, clicking between those symbols, and pressing your enter key. This will cause them to space out, and allow you to type a property. 
    - Our first property will be `color`.
    - Type a `:` after color, which allows you to set a value.
    - Set the value to `blue`.
    - Type a `;` at the end of the line to let the browser know that command is complete.

    Right now, your code should look like this:

    ```
    p {
    color: blue;
    }
    ```

## Check Your Work
5. [ ] Verify that your work is correct, and fix any issues. This is an essential step whenever we make changes.
    - Let’s view that in the browser to see what it looks like. 
    - Troubleshoot any issues for a few minutes with AI first, then ask your instructor for help if needed.

## Set Background Color
6. [ ] Set a background color for the entire page.

    - Just like when we wrote our paragraph color selector, select the `body` element.
    - Then, open your declaration block with curly braces `{}`
    - Now, let’s tell it we want to change the `background-color` property
    - Don’t forget your `:` followed by a space
    - Set the value to `beige`, and don't forget your `;` to finish the command
    - Now, the contents of your CSS file should look like this:

    ```
    p {
    color: blue;
    }

    body {
    background-color: beige;
    }
    ```

## Check Your Work
You might be noticing a pattern here - always check your work!

7. [ ] Verify that your work is correct, and fix any issues. This is an essential step whenever we make changes.
    - Let’s view that in the browser to see what it looks like. 
    - Troubleshoot any issues for a few minutes with AI first, then ask your instructor for help if needed.

## Adjust Heading Font Size
Let’s increase the font size of the most important heading to make it more prominent.

8. [ ] Increase the heading font size.
    - Just like before, start by using an `h1` selector to target `h1` elements
    - Then, open your declaration block with curly braces `{}`
    - Put `font-size:` followed by a space and `24px;`

    ```
    h1 {
    font-size: 24px;
    }
    ```

## Check Your Work
You might be noticing a pattern here - always check your work!

9. [ ] Verify that your work is correct, and fix any issues. This is an essential step whenever we make changes.
    - Let’s view that in the browser to see what it looks like. 
    - Troubleshoot any issues for a few minutes with AI first, then ask your instructor for help if needed.


## Update a Value
Now that we’ve set some basic properties and their corresponding values, let’s update some of those values. Using the named colors in CSS, we can update our colors quickly to more aesthetically pleasing ones. Instead of rewriting everything, we can update the values of the code we’ve already written while leaving everything else the same.

10. [ ] Update your color values.
    - Change the value of `background-color` to `beige`
    - Change the value of `font color` to `steelblue`

### Final Check

11. [ ] Once more, let’s view the changes made to the webpage and troubleshoot any mistakes. Use AI and your instructor for suggestions and corrections if needed.

## Congratulations, you did it!
CSS is a very powerful scripting language that allows us to make the most beautiful websites and applications in the world, and you've just taken your first steps with it. While it can be daunting at first and takes time to master, with knowledge and practice, its unique ability to create precise and creative visuals just might make it one of your favorite languages.

## Switch to the next branch
Now, it's time to switch to the `solo` branch and try to tackle an activity with the help of your AI and with your instructor's support should you have questions or run into any trouble. Do so now with the following command.

```
git checkout solo
```