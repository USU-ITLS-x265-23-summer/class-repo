# Project Help References
- So this is something that I decided to create so that we can all contribute to add things that have helped us with preparing for our projects. This can include helpful programs or videos.

## File Organization
- [Simple File Organization Video](https://www.youtube.com/watch?v=ta3Oxx7Yqbo)

## Code Editors
- [Light Table - Open Source & Free](http://lighttable.com/)

## How to Host Website
- [GitHub Hosting](https://www.youtube.com/watch?v=p1QU3kLFPdg)

## Live Edit Extension
Microsoft has created a super handy extension that shows you what your HTML looks like! (And stylized as well!)

The extension is called Live Preview! To add it to your repository, click the extensions tab on the far-left side. This page should be familiar because this is where you installed codespaces. Search "Live Preview" and then install the tool.

Read over the features to understand specifics on how it works. I like this extension compared to other preview extensions I have used because this one automatically showcases the changes you make without you having to re-open the preview. 

I wasn't sure if anyone else was using less-effective preview tools like I was, so I thought I would add this here. :) 

## Tips for creating your own portfolio using CSS, HTML, and JS
- [Creating Your Own Portfolio Using HTML, CSS, JS, and Bootstrap](https://www.freecodecamp.org/news/how-to-create-a-portfolio-website-using-html-css-javascript-and-bootstrap/)
- Similar to the link above, but with some different tips: [How to Build Your Own Developer Portfolio](https://www.freecodecamp.org/news/how-to-build-a-developer-portfolio-website) 

## I can't see my edits inside of GitHub?! Help!!
This is for those of you who are coding inside of visual studio in a codespace. You have made changes but they aren't appearing here inside of GitHub. Let me show you how to update GitHub
so you can view your updates! I know this is covered in the project template, but here is a different way to commit and push your code.

To update your repository, you are going to use what is called a shell - lucky for you, there is one already integrated straight into Visual Studio. It is listed as "Terminal" on the bottom
section of options.

This may look a little scary at first, but I promise it isn't too bad! 

When you first look at the terminal, you should see something like `@user -> workspaces/[YOUR-PROJECT-REPO] main$ `.

This is where you are going to type your commands. Updating your repo inside of GitHub is a two-step process.

First, you need to *COMMIT* your changes:
To do this, type: `git commit -am "INSERT UPDATE MESSAGE HERE"`
The `a` argument tells git that you will be committing ALL edited files. The `m` argument gives this commit a message. You should always message your commits, so you can verify them later.

Note: If you receive a message saying that your branch is up to date, that means that you don't have anything to actually commit. No changes have been detected.

After you commit, it is now time to *PUSH* your changes:
This step is super easy! 

In the terminal, all you're going to type is `git push`. (Yes - that's really it.)

Once you do this, your changes will be uploaded to GitHub, and you will be able to view them here. 

If you need any help, post a post in the discussion and tag me (@coopsand) somewhere in the body. I can do my best to help you there.

You can also consult [this link](https://www.atlassian.com/git/tutorials/saving-changes/git-commit) for additional help and information.
