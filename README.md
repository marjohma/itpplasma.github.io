# itpplasma.github.io
----
## Welcome to the (new) Homepage of the Plasma Physicist's at TU Graz!

This _README_ will give a short intoduction to the Github-Pages structure of [itpplasma.github.io](href="https://itpplasma.github.io/"). It's supposed to help add posts, edit pages or the whole site, and give some explanations to the html-background "code". 

To this date (20.04.2023), both the github page as well as this readme are yet to be finished, and if you're reading this (also at a later point) and this sentence here has not been deleted yet, you will find this repository in, well, quite a messy state. I'm very sorry for that, I'll try to fix it as soon as possible!

If you want to add some information or a post to the ITP Plasma Homepage, and you cannot find instructions in this _README_ yet, I'm still working on the structure of the ==page==. In this case, please get in touch with me, ideally at the next meeting or via e-mail: vkeusch@student.tugraz.at Thanks a lot!


#### Markdown and HTML

The majority of this Github Page is written in either Markdown (for text and so all of the content) or HTML. [Here you can find a Cheatsheet for Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), as most of the content is/will be in Markdown files (as it's easier to write and read than html, at least in my opinion).

### Main Content:

Comparing [itpplasma.github.io on Github](https://github.com/itpplasma/itpplasma.github.io) with [itpplasma.github.io](href="https://itpplasma.github.io/"):

**In Main:**

* The "Home" page/starting page (https://itpplasma.github.io/) can be found in [index.md](https://github.com/itpplasma/itpplasma.github.io/blob/main/index.md).
* [Research](https://itpplasma.github.io/research) is [research.md](https://github.com/itpplasma/itpplasma.github.io/blob/main/research.md). _Here it maybe would be nice if every Topic/Working Group from the Kan Ban could write a few sentences about their research topic, maybe include a few pictures and references to team members and publications if applicable_
* The Publications link right now leads directly to [itpplasma at Zootero](https://www.zotero.org/itpplasma). So publications.md is currently not in use.
* ==[News](https://itpplasma.github.io/newsupdates.html)== can be found at [newsupdates.md](https://github.com/itpplasma/itpplasma.github.io/blob/main/newsupdates.md). Depending on what's easier to read and use, you can edit the News directly in there, by maybe just making a new header and writing below, or as it is currently also on display, you can write a seperate "post" for each new News article. The posts can be found in the [\_posts](https://github.com/itpplasma/itpplasma.github.io/tree/main/_posts) directory, where two examples can be found. All the posts are automatically displayed (by the lines 28 to 54 in newsupdates.md) with their whole content in the News-Section. If the news are longer, this can be changed to just displaying the title or the first few sentences, where then the post link leads to the full news entry.

**Folders:**

* Viki's Trial and Error Grounds: A graveyard for past ideas (mainly layouts), as I didn't want to delete them immediately but wanted to commemorate them. Please do not touch, other than to maybe delete the whole folder eventually if I don't do it myself.
* [\_includes](https://github.com/itpplasma/itpplasma.github.io/tree/main/_includes) includes parts of the overall layouts. most importantly:
        * [navbar.html](https://github.com/itpplasma/itpplasma.github.io/blob/main/_includes/navbar.html) where the Navigation Bar at the Top with the links to index.md, the News, Team, Research, and Students sections can be found. 
        * [footer_new.html](https://github.com/itpplasma/itpplasma.github.io/blob/main/_includes/footer_new.html) and
        * [head.html](https://github.com/itpplasma/itpplasma.github.io/blob/main/_includes/head.html), which now only inlcudes the ITPCP and TU Graz logos and links on the top corners
* [\_layouts](https://github.com/itpplasma/itpplasma.github.io/tree/main/_layouts) including the [newdefault.html](https://github.com/itpplasma/itpplasma.github.io/tree/main/_layouts/newdefault.html) layout _which all "normal pages"_ use as their default layout. (Has to or well should be included with `--- (Absatz) layout: newdefault (Absatz) --- `. The [post.html](https://github.com/itpplasma/itpplasma.github.io/blob/main/_layouts/post.html) is exclusively used for posts in \_posts
* [\_posts](https://github.com/itpplasma/itpplasma.github.io/tree/main/_posts) (see News above)
* [assets](https://github.com/itpplasma/itpplasma.github.io/tree/main/assets) inlcuding all pictures/images 
* [students](https://github.com/itpplasma/itpplasma.github.io/tree/main/students) where the student's sections can be found and last but definitely not least
* [==team==](https://github.com/itpplasma/itpplasma.github.io/tree/main/team) Here you can find the [Team](https://itpplasma.github.io/team/team.html) section. Please add your name, position, research areas/topics as well as a few sentences about yourself and your research. Please also feel free to include a picture of yourself if you like. There was also an idea of including 2-3 "interview-style" questions, such as "Why are you in fusion research?" or non subject-specific "What's your favourite food?"


----
[![pages-build-deployment](https://github.com/itpplasma/itpplasma.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/itpplasma/itpplasma.github.io/actions/workflows/pages/pages-build-deployment)
