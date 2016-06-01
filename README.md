# Personal Site Project - Part 4

## Objectives

1. Add CSS style to HTML pages. 
2. Save your work and publish to Github

## Instructions

It is time to put what you have learned into practice and grow confidence by building on your own. Below are the step by step instructions you can use as a general guide. Feel free to add more things if you wish or leave things out if they do not apply to your projects needs.

1. In Terminal, change directory into the folder for your project you created previously in part 1 `cd <your-project-name>`.

2. Make sure you are on your master branch `git checkout master` and create a new branch called site-style like so: `git checkout -b site-style`.

3. Create an external CSS file `mkdir css`, and `touch css/style.css`.

4. Next, open your favorite code editor and make sure to include at the minimum the following things in your projects HTML & CSS page(s):
  - link to your external stylesheet from the head section fo your html pages.
  - Apply selectors for class, id, and descendent selector
  - Try Styling text color and fonts.
  - Optionally add a webfont from Google Fonts.

5. Once your finished, preview your code in the browser and if you're satisfied with the way it looks and all code validates. Go ahead and stage, and commit your changes `git add .`, `git commit -m "part 4"`.

6. Then let's merge this branch into master. First `git checkout master`, then `git merge site-style`.

7. Then push it up to your remote `git push origin master`.

8. Then lets merge this branch into gh-pages to see it live. First `git checkout gh-pages`, then `git merge master`.

9. Then push it up to your remote `git push origin gh-pages`.

<p class='util--hide'>View <a href='https://learn.co/lessons/html-css-personal-site-project-part-4'>HTML CSS Personal Site Project Part 4</a> on Learn.co and start learning to code for free.</p>
