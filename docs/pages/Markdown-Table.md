---
title: Markdown Table
layout: default
excerpt: Place the introducing line of text ie.) the 'tagline' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Markdown-Lessons-Project
ver_date: 11-20-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## First Subtitle

> **Hint**. {{ page.hint }}

More to come ...

### How To Create A Table In Markdown

- First, make a new repository at GitHub

- Give the new repo the name of 'Markdown-Lessons-Project'

- Add a Description to the new repo, as follows:

- A repo of Markdown Lessons hosted by GitHub Pages

- Leave the default Public ( You can still choose who can commit changes after forking the repo )

- Check the box 'Initialize this repository with a ReadMe

- Add .gitignore VisualStudio

- Add a license GNU Affero General Public License v3.0

- Click the green 'Create Repository' button

- GitHub automatically creates and displays your repo

- Click the green 'Clone or Download' button

- Click 'Open In Desktop'

- An alert box will pop up where you can further choose to 'Open GitHub Desktop.app'

- Click 'Open GitHub Desktop.app'

- **Note**. If you need to install a copy of the GitHub Desktop.app for Mac Os, follow this [link](https://desktop.github.com/){:target="_blank"}.

- A Finder window from within the GitHub Desktop.app will open on your Mac at your 'repos' folder with the title to your new repo auto-populated in the top 'Clone As' address line.

- Click the 'Clone' button located in the lower right of the now open Finder window to place your new repo in the 'repos' folder of your local machine.

- The GitHub Desktop.app will now open to your new repo and display your initial commit in the History tab of your new local master.

- Open up a new window in Visual Studio Code and navigate to the location of your new repo.

- **Note**. If you need to install a copy of the Visual Studio Code for Mac Os, follow this [link](https://code.visualstudio.com/download){:target="_blank"}.

- Open your new repo at the main folder name.

- Visual Studio Code will then present the name of your repo in the left-hand explorer window-column followed by the three (3) files you created at the inception of the repo, the .gitignore, the License, and the ReadMe.

- Select the .gitignore file by double-clicking after hovering over the name and then overwrite the contents of the default .gitignore template with your own most recent local .gitignore template, if you have created one.

- **Note**. Simply copy, select all, and paste, now save.

- Returning to your local copy of the GitHub Desktop.app for Mac Os program, you will see that we now have one (1) uncommitted change to deal with.

- Keep your branch at the local master and add a summary to the commit, as follows:

- 'Update git ignore template'

- Next, type a description of your commit, as follows:

- 'Overwrite all with contents of local template Dtd 060217'

- Click the button 'Commit To Master'

- Your changes have been added to the local master.

- Now, to sync your local master with the remote master sitting up at the Google Server farm, click the 'Sync' button in the upper right hand corner of your GitHub Desktop.app screen

- Clicking the history tab above reveals your new pull has been accepted by the remote master.

## Git Hub Pages

- We are now ready to establish Git Hub pages for your new repo.

- First, we must locally add the folder 'docs' to your new repo along with an index dot markdown file housed within the same 'docs folder, as well.

- In Visual Studio Code, still open to the contents of your new repo ...

- Right-click after hovering over the name of your new repo and select the 'add new folder' icon.

- Type the name 'docs' for your new folder.

- This will create a folder named 'docs' in your directory, one level up from the root of your repo.

- From this new 'docs' folder, all of your new Git Hub Pages will be served both locally, and remotely.

- The root folder of your repo will then in effect become partitioned from your Git Hub Pages folder.

- **Note**. The root folder of your repo currently houses the 'git' files of your repo, and will soon house your ruby gem and gem dot lock files, as well.

- But, first ... We must sync the local master with the remote master once again.

- Before that, however, let's add the 'index dot md file' to the local 'docs' folder of your repo.

- The 'index dot md file' is a markdown file and as such requires the addition of front matter up above at the beginning of the file.

- Let's install the front matter of the 'index dot md file' with the following terms:

### The Front Matter Code

```liquid
{% raw %}
---
title: Home Page
layout: default
navigation_weight: 1
---
{% endraw %}
```

**Note**. Place the above code snippet at the very top of the blank 'index dot md file' that we have created.

By doing so, we have imbued the front matter of the page with the 'Home Page' title to the 'index dot md file', a default layout, and a navigation weight of one (1).

## Placeholder Text

To round out the 'index dot md file', place the following placeholder text directly below the last border line of the front matter section, as follows:

```liquid
{% raw %}
---
title: Home Page
layout: default
navigation_weight: 1
---
# Issue: Lesson Template

## State the issue of the problem in the form of a question

## Solution

Expound the solution ...

## The Code

Highlight the code ...

## Summation

Delineate the steps ...

## Live

Render the code live
{% endraw %}
```

## Git Hub App Commit

Going back to the Git Hub app, go ahead and commit the changes to the local master and hit sync to keep the remote master up at the Git Hub server farm in tune.

You now have a fully synced index dot md file inside the required docs folder.

That is all that is required to 'switch on' rudimentary Git Hub Pages for your new repo.

But, this has to be done remotely, so in your Chrome browser ... login back into your Git Hub repository if need be.

Otherwise, your remote repo should still be in the first tab of our Chrome Browser.

**Note**. If you need to install a copy of the Chrome Browser for Mac, follow this [link](https://www.google.com/chrome/browser/desktop/index.html){:target="_blank"}.

## Remote Repo Settings

Next, click the settings tab of your remote Git Hub repo and scroll down about half-way.

There, you will see instructions on how to enable Git Hub pages for your repo.

First, select the source 'Master Branch/Docs Folder' and click save.

Secondly, select the 'Theme Chooser' button and select the theme 'Cayman'.

The asynchronous reply front the remote server will be the text 'Your site is currently using the Cayman theme.'

Congratulations! You have added the rudimentary, basic Git Hub Pages to your repo using the 'Cayman' theme.

To test, click the new link address to your repo's Git Hub Pages website ... Next to 'Your site is ready to be published at'.

A browser window should open to the home page of your repo's Git Hub Pages website.

And, indeed it does!

## Synch Locally

Now that we have made all of these new changes to the remote master while setting up our initial Git Hub Pages website, we must sync our local master with the remote to capture all of these new changes locally.

Go back to your 'GitHub Desktop.app for Mac Os program'.

Already open to your repo, keep your local master engaged, and simply hit the sync button.

Your local master is now at par with your remote master.

To confirm, you will see in the history tab of your local master, the commit from the remote titled 'Set theme jekyll-theme-cayman' where the theme 'Cayman' has been set within the new 'config dot yaml file'.

In Visual Studio Code, still open to your new repo, you will see the new file in the explorer window as titled `_config.yml`.

It is now time to set up a working branch locally.

## Local Working Branch

With the history list still showing for your master branch at your local 'GitHub Desktop.app for Mac Os program', click the 'add a branch' icon in the upper left hand corner.

Type in a name for your new local working branch ie.) 'Working-Weber-1' and hit the 'Create Branch' button.

From now on, all local changes to your repo will be committed and accumulated through this working branch.

In effect, the remote master branch has now become partitioned from your work locally.

You must, therefore, commit each change locally to your local master and then issue a pull request that can be accepted by the remote master prior to becoming part of the remote master.

## Jekyll Server

To review your changes locally, prior to generating a pull request that can be accepted by the remote master, you must install the Jekyll server on your development machine.

Lucky for us, this is an easy step that can be accomplished with the 'gem bundler' program.

First, let's create a 'gem-template' that can then be reused for multiple repos, including the subject repo, and we'll include the raw code here.

But, first I'll have to move this 'Markdown-Table' file to the 'pages' subdirectory of the new repo.

From the 'docs folder' in Visual Studio Code, right click and add a new subdirectory called 'pages'.

From the Finder, move 'Markdown-Table.md' to the new 'pages' subdirectory.

## Includes

In addition, From the 'docs folder' in Visual Studio Code, right click and add a new subdirectory called '_includes'.

## Gem Template

Next, place the contents of the gem-template into a new file name 'gem-template.htm' located in the a new 'underscore includes' subdirectory of the 'docs folder'.

Finally, include the gem-template contents here, as follows:

```liquid
{% raw %}
{% include gem-template.htm %}
{% endraw %}
```

## Gemfile

The 'Gemfile' is where you manage all of your Jekyll Server versioning and is automatically generated by the 'Gem Bundler' program in the root of your repo.

From the root of your repo located via the Finder, right click and select 'New Terminal At Folder'.

This will initiate a Terminal session where we can invoke the 'Gem Bundler' program.

## Ruby Version Manager

First, change to Ruby 2.4.1 via the 'Ruby Version Manager'.

**Note**. If you need to install a copy of the Ruby Version Manager for Mac, follow this link ... [Ruby Version Manager for Mac](https://rvm.io/){:target="_blank"}.

From the Terminal prompt,

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

## Time To Bundle Install

Now that we have the Gemfile sitting in the root directory of the repo ( NOT in the root directory ie.) '/docs' of the website ...! ) and configured properly with the contents of the local gem-template, we must now invoke the 'Gem Bundler' and install all of the dependencies required by the 'Gem Jekyll', as follows:

From the Terminal prompt set to the root directory of the repo, type the following command:

```liquid
{% raw %}
bundle install
{% endraw %}
```

## Gemfile dot lock

After running the Terminal command, you will see a message, as follows:

> Bundle complete! 11 Gemfile dependencies, 76 gems now installed.

## Config dot yaml

Now that the 'Gemfile dot lock file' is complete and the installation of the dependencies is behind us, it is time to go to work on sprucing up the configuration file auto generated at the time we established Git Hub Pages for the repo remotely.

The configuration file is named '_config.yml' and has been auto-placed in the root directory '/docs' of the website by the remote server with one simple line of code ... the declaration designating the 'Cayman' theme.

## Google Analytics

Each repo deserves a separate Google Analytics number. Go to the admin section to establish a unique number for your repo.

If you need to establish a Google Analytics account, follow this link ... [Google Analytics](https://analytics.google.com){:target="_blank"}.

## Config Template

When you are satisfied with the contents of your 'config-template', copy and paste the contents to the local '_config.yml' overriding the remote generated file.

Then commit your changes to the Working branch of your local repo and generate a pull request for the remote server.

## Remote Settings

After each successful commit, pull, and merge with the remote master ...

Go to the Settings tab of your repo and click on the URL of your Git Hub Pages website.

If there are any problems with your configuration as presented and merged, the URL will not render.

In this case, it does!

## Cayman Theme

The remote server has set the default for a simple 'Cayman Theme'.

To grant the website additional function, we shall import a couple of files from the local copy of the theme 'Cayman'.

## ICO

First, from the Finder ... drag in a favicon (.ico) to both the repo root and the website '/docs' root.

## Data

Establish a '_data' subdirectory and fund the folder with the 'new-data-template.json'

## Layouts

Next, establish a '_layouts' subdirectory and fund the folder with the 'default.htm'.

The include(s) icon-github.html', 'nav.htm', and icon-github.svg are required for the proper functioning of the 'default.htm'.

Place these three (3) includes in the new '_includes' subdirectory.

## Sass

The entire '_sass' subdirectory must be duplicated from the 'Cayman' theme local copy and moved into the '/docs' directory of your repo.

There are four (4) files inside the default '_sass' subdirectory.

We shall utilize them all in addition to the local custom style sheet 'style.scss' stored in the 'assets/css' directory of the '/docs' website root.

1. jekyll-theme-cayman.scss

1. normalize.scss

1. rouge-github.scss

1. variables.scss

## Assets

Be sure to drag in ( if already made ), or create an 'assets' subdirectory as a sub-folder of the '/docs' directory.

Next, create the 'css' subdirectory below the 'assets' folder to house the custom style sheet referenced above.

And, create the 'ico' subdirectory below the 'assets' folder to house any 'ico' images as well as create the 'img' subdirectory below the 'assets' folder to house any other types of images.

## Commit and Pull

Finally, commit your changes to the local Working branch and issue a pull request to the remote master via the local GitHub desktop.app and test the rendering remotely via the GitHub Pages tab by clicking the URL for your new website.

## MMINAIL

There is a Markdown folder in the navigation aside of the MMINAIL home page. If you click on the 'Learn Markdown' sub-tab in the drop down menu, you will see a series of links that will hyperlink the end-user to the markdown pages complete with a link-back to the home page of the MMINAIL embedded in the footer of each (.md)

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}
