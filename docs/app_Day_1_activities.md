## Day 1 Activities

### Add a New Slide

Just like we did in class, open a new pull request adding a new slide to the deck.

1. Create a new branch, and checkout to that branch: `git checkout -b NEWBRANCHNAME`.
1. Create a new file in the `_posts` directory, named by date and description like YYYY-MM-DD-username-description.md. (The date has to be in the past - future dates won't show up.)
1. Follow the directions for the same activity we created together, where it says "[Activity: Edit Your File](https://githubtraining.github.io/training-manual/#/06_working_locally)".
1. Instead of just adding the caption, you will need to find a new image from the image list and use that to fill in this template:
        ```
        ---
        layout: slide
        ---

        IMAGEURL
        {: .center}

        CAPTION-HERE
        {: .fragment}
        ```
1. Save and commit your changes on your new branch.
1. If working locally, push your changes up to the remote: `git push -u origin NEWBRANCHNAME`.
1. Open a pull request
In the body of the pull request, @ mention anyone you'd like to review your changes.
1. Once the tests pass on your pull request, merge the pull request.

### Add a Caption To an Existing Slide

Add a caption to an existing slide in someone else's pull request.

1. Find a pull request that you'd like to add a caption to.
1. See what image they have chosen by clicking 'files changed', and then 'view'.
1. Edit the file, either in the browser or locally, to add a line with your caption. (Please do not erase work that others have added to this file.)
    - If you are working locally, you will need to check out to the branch.
    - Make sure you have all of the remote changes updated in your local repository: `git pull`.
    - Look for the name of the branch in the pull request, and check out to that branch locally: `git checkout BRANCHNAME`.
1. Save the changes, and commit the file.
    - If you are working locally, push the changes up to the remote: `git push`.
1. Do not merge the pull request, simply `@` mention the user who opened the pull request to let them know about your changes.

### Improve the `README.md`

Improve our `README.md` by adding some of your favorite resources.

1. Create branch, and checkout to that branch: `git checkout -b NEWBRANCHNAME`.
1. Edit the README.md to be better in some way. This could mean adding a new resource, or making the existing descriptions more clear. Save and commit your changes.
1. If working locally, push your changes up to the remote: `git push -u origin NEWBRANCHNAME`.
1. Open a pull request
In the body of the pull request, with `base: master` and `compare: NEWBRANCHNAME`.
1. `@` mention anyone you'd like to review your changes.
1. Once the tests pass on your pull request, merge the pull request.

### Restyle Slides

If you'd like a more advanced challenge, and you have an eye for style, change the colors, font, and other aspects of the class slide deck. **Note: If multiple participants attempt this, there may be merge conflicts.**

1. Create a new branch and check out to it: `git checkout -b NEWBRANCHNAME`.
1. Find the file `_sass/solarized/solarized.scss`.
1. Make changes in the file.
    - Lines 12-19 affect colors
    - Lines 33-35 affect font and font size
    - Lines 52-55 affect headers
1. Save and commit your changes on your branch.
1. Push your branch to the remote: `git push -u origin NEWBRANCHNAME`.
1. Open a pull request with `base: master` and `compare: NEWBRANCHNAME`.
1. `@` mention anyone you'd like to review your changes.
1. Once the tests pass on your pull request, merge the pull request.
