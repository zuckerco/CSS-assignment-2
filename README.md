#CSS Assignment 2 (Assignment 4)

This repo contains your assignment starter files, including three images.

1. **Fork** this repo (make sure you are logged into GitHub).

2. **Clone** your new repo so you have it on your hard drive. Remember to save it into the folder where you are keeping all your projects for this course.

3. Use your GitHub app to create a **local branch** named *gh-pages*. Switch to that branch and do all your work in that branch. Note that the hyphen and all lowercase letters are essential.

##Part 1

Use the files *index.html* and *main.css* provided. DO NOT change *index.html* in any way.

You must write style rules in *main.css* to make the HTML page (*index.html*) look similar to the first "Sea Mammals" page in [this video]. Note that a color palette has been provided in *main.css* -- our focus here is not on colors but on margins and padding, as well as effective use of CSS selectors.

1. Specify background colors for the three `section` elements, using the IDs that are in the HTML. Each `section` must have a different background color.

2. Specify a width for the `article` element and give it a white background.

3. Figure out how to center the `h2`, `img`, image source paragraph, and the `article`. There are two different methods for centering. **DO NOT center the text inside the `article`!**

4. Specify padding for `article`.

5. Center the text in the `footer` and specify padding.

6. In the `header`, use the **width** property, the **float** property, and techniques for making a navigation bar (Robbins chapter 15) to set up the header as shown in the video. **DO NOT change any of the HTML in *index.html*!**

7. Adjust margins and padding as needed to finish the page and make it look nice.

##Part 2

Now you will make a different page layout using the same HTML file and new CSS. Make sure you've finished Part 1 first.

Copy the file *index.html* and name the new one *twosides.html*. Copy your final *main.css* and name the new one *twosides.css*. Edit the `link` element in *twosides.html* to attach the new style sheet file.

You will make your second "Big Cats" page look similar to the second "Sea Mammals" page in [this video].

1. The new layout will be easier to create if you wrap the `h2`, `img` and image source paragraph in one `div`. This is the ONLY change you may make to the HTML. Do exactly the same thing for each of the three `section` elements in *bigcats.html*.

2. Use the CSS **float** property to achieve the side-by-side layout shown in the video. This will be tricky and frustrating. The best way to learn floats is to try, try, try. Lots of saving and reloading. Do not add a lot of CSS declarations -- more is NOT better. Keep it simple. Pay attention to Robbins's advice about the **clear** property. Robbins's section "Containing floats" will also be helpful.

3. You will find that *percentages* will work better than *pixels* for widths on the two sides.

4. Remove the white background from `article`.

5. Adjust padding and margins as needed to finish the page and make it look nice.

Do not use the **position** property on any part of the `section` or `article` here. Floats will work.

##Part 3

When you have finished, you must **commit and sync** to GitHub. Don't forget to post the URL of your GitHub repo in Canvas before the deadline!

Do not make a pull request.

There is a bonus to your new branch. By naming it *gh-pages* you are taking advantage of a GitHub feature that allows us to publish live Web pages. After you commit and sync, you can see your handiwork here:

http://[ your username ].github.io/CSS-assignment-2/

And here:

http://[ your username ].github.io/CSS-assignment-2/twosides.html

If you need to fix anything after your first commit-and-sync, you will need to commit and sync AGAIN to get your changes up on GitHub. Don't forget to do all your work in your *gh-pages* branch!
