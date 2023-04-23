---
share: true
cat: projects
---
# sandrigos notes
# ...or: how to set up an Obsidian-powered notes website for FREE in 3 easy steps!

## What ist this site?
I started to use [Obisdian.md](http://Obisdian.md) in early 2023, after finding it through some random YouTube Video. I got hooked on the idea to have a reliable, lightweight but also appealing note-taking tool, or more of a "second brain". 

I soon started to put in my video-ideas, notes on technologies for programming projects, my banking informations or other personal information i need to access at all times.

I found some websites or so called "digital gardens" of other people and found it kind of nice. So i started to check out the various options to host Obsidian notes in an reliable way, for zero cost and with easy handling - cause that's how i like it 😁

## Technological overview
It seems there are different ways to turn Obsidian notes into a website, but ultimately i settled for a template using _[[Github]]_, _[Github Pages](https://pages.github.com/)_, _mkDocs_, _mkDocs Material_ and for publishing i use the Obsidian Plugin _Github Publisher_. 

## Technological details & HowTo set up the website
I explain the "moving parts" and the steps to set up your own Obsidian notes website in __3 easy steps__!

#### Use the template to create website foundation and repository
- First i used the template called _obsidian publish mkdocs_ from [Jobin John](https://github.com/jobindjohn) which can be found here on Github:
	[https://github.com/jobindjohn/obsidian-publish-mkdocs](https://github.com/jobindjohn/obsidian-publish-mkdocs)

- You follow the instructions and use the template to create your own _Github_ repository, which then will be the base of your new homepage on _[Github Pages](https://pages.github.com/)_. The template creates the folderstructure for _mkDocs_ which is a neat little project over at [https://github.com/mkdocs/mkdocs](https://github.com/mkdocs/mkdocs) - which creates HTML websites out of Markdown files - exactly what we need!

- The template and website will then automatically (rather "automagically🪄""!) be hosted on [<YourGithubUsername.github.io/Repositoryname>](<YourGithubUsername.github.io/Repositoryname>)

#### Upload your files to fill your website with notes and life!

- Now after the site is running, you can  `git clone`  your new repository and just upload/commit your _"Note.md"_ files to the _GithubRepoName/docs_ folder - every note is counted as a new page. You can create folders of course, they act as your "menu entries" -  technically the Obsidian note website now working, but we dont't stop here!

#### Use Obsidian Github Publisher to automagically🪄 upload your notes to Github
- Like the title says, we use the Obsidian plugin _Obsidian Github Publisher_  which can be found here:
	[https://github.com/ObsidianPublisher/obsidian-github-publisher](https://github.com/ObsidianPublisher/obsidian-github-publisher)
 We use the plugin in Obsidian itself to start synchronizing and uploading new notes to the corresponding folders. You just have to connect your Github account to the plugin, set the folders and maybe some settings (for example i activated a shortcut so i can specify a category, which are the folders, for each note) - and you are good to go! ✨✨✨

--- 

And that's it, really! You only need to adjust the `mkdocs.yml` to your liking (website title, colors and all that buzz), and there you go, your own, on Github Pages for free, git-controlled, automagicall🪄, modern, Obisdian-powered, digital garden for everyone to see and enjoy! 😍👌

I hope i could help you with your setup, if you have questions or comments feel free to contac me, my contacts are on my Github page - [https://github.com/sandrigo](https://github.com/sandrigo)
Greetings, Sandrigo


%% #obsidian #website #mkdocs #github #howto #projekt %%