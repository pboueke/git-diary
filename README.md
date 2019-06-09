# [A git diary](https://pboueke.github.io/git-diary/index.html) 

 This repository is managed by an instance of the [git-diary-api](https://github.com/pboueke/git-diary-api).You can view the static rendering of the diary [here](https://pboueke.github.io/git-diary/index.html).

The git-diary project aims to provide an absolutely basic diary/blogging experience backed by a git repository. The chosen repository must contain a folder named `posts`, and that's it. The details of setting up the repository are explained in the [git-diary-api](https://github.com/pboueke/git-diary-api) project, which is responsible for managing the repository.

Blog posts are written in markdown and saved as plain text in files named as `yyyy-MM-dd-Post-Title.md`. 

This is a very simple project aiming to provide basic file management over a git repository. The API provides an easy way to integrate this solution in file editors, chat bots and whatever else. 

If you are looking to set up a diary, simply create a new repository with a folder named `posts` and set up the api following the steps described [there](https://github.com/pboueke/git-diary-api). If you want the static rendering to be public, enabled github pages in your repository and copy the `index.html` file to it, editing whatever you fell like editing. 