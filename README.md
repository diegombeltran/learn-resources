# Learn Resources

## What does this do?
A friend and I thought that it would be a great idea to put learn resources into a simple, static website full of bookmarks. [Static Marks](https://github.com/darekkay/static-marks) by **Darek Kay** is used to create this simple site using yaml files inside _files_ folder.

## How?
In the past this was done with GitLab CI. As we tried to learn a bit about GitHub Actions, the pipeline is hosted here now.
The pipeline itself is very simple: it fetches the code inside an Ubuntu runner, sets Node.js up, installs Static Marks, and generates and deploys to a different branch _gh-pages_, which is published and accessible from a GitHub subdomain.

## Where can I access the bookmarks?
[Here](https://diegombeltran.github.io/learn-resources)

## Can I contribute?
For the moment it's private, but it may be opened in the future. We will update the README accordingly.
