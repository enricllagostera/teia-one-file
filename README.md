# Teia

A one-file wiki (using [TiddlyWiki](https://tiddlywiki.com/)) with some configuration and a few extra features to facilitate research writing and reading.

## How to use

The text of your notes, settings and system related info are stored in the `index.html` file. There are two main ways to interact with it:

1. You can open that file in any browser and start using it;
2. You can open it using the TiddlyDesktop application;

You can use the folder in which your `index.html` file is located as the root of your wiki. You can then create folders in your file explorer, copy and move files, and then link to them in your notes.

### Using your wiki in a browser

If you are using your wiki via a browser, you'll have to define your saving options in the `Settings > Saving` menu. The two best options there are to use either the *Download Saver*, which will download a new copy of the wiki to your computer, or the *GitHub (or GitLab) Saver*, which will commit any changes to a repository on that specific service.

### Using your wiki via [TiddlyDesktop](https://tiddlywiki.com/static/TiddlyDesktop.html)

I recommend opening the wiki via the [TiddlyDesktop](https://tiddlywiki.com/static/TiddlyDesktop.html) app. I have found that it helped me to streamline saving changes and to avoid distractions on the internet.

 When using the app, changes will be automatically saved in your local files. This avoids the need to always download a new version of your `index.html` file or to setup authentication tokens for GitHub (or GitLab). It also works well when offline.

After saving your files locally, you can then commit your changes to a repository if you are using some versioning system (and maybe push to an online service). I strongly recommend you do this, so you can keep track of past versions and have organized back-ups.
