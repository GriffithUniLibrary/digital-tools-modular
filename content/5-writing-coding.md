## Coding <span class="fas fa-rocket"></span> 

# Work with text

{% capture text %}
    Plain text editors are much more important than you might think. Get yourself a good one.
    {% endcapture %}
    
{% include alert.html text=text color=info %}

**Recommended**
 - [Sublime Text](https://www.sublimetext.com) is one of the most popular programming text editors for Windows
 - [Notepad++](https://notepad-plus-plus.org/) is a popular free option
 - [BBEdit (Mac)](https://www.barebones.com/products/bbedit/) is a venerable (30y+) program with many fans in the Mac world. This website is currently being edited in BBEdit.

**Other tools**
 - [Atom](https://atom.io)
 - [Brackets](http://brackets.io)
 - [Visual Studio Code](code.visualstudio.com)

### Markdown editors

`Markdown` is a simple and popular text formatting syntax. It's worth becoming familiar with it. This site is written in Markdown.

**The tools**
 - [Dillinger](https://dillinger.io) and [Stackedit](https://stackedit.io) are popular and free online Markdown editors.
 - [Ulysses](https://ulysses.app) is a general-purpose writing app with good Markdown support.
 - [Marked 2 (Mac)](https://marked2app.com)

{% capture text %}
    **What's a development environment?**
    It's a set of tools that allow you to write, debug, build and run code. Some development environments support a single language  or platform (like R), and some (like Visual Studio) support multiple languages and platforms.
    {% endcapture %}

{% include alert.html text=text color="info" %}

{% capture environments %}
    - [R](https://www.r-project.org) - extensible, support through Hacky Hour and Carpentries
    - [Python](https://www.python.org) - support through Hacky Hour and Carpentries
    - [GitLab](https://gitlab.rcs.griffith.edu.au) - Griffith University shared code repository
    - [Visual Studio](https://visualstudio.microsoft.com) - mulitiplatform IDE published by Microsoft
    - [GitHub](https://github.com) is a popular code repository site. This site is hosted on GitHub.
    - [Anaconda](https://www.anaconda.com/distribution/) Python development environment
    {% endcapture %}

{% include card.html header="👾 Development environments" text=environments %}

{% capture text %}
     - [Software carpentry](https://hackyhourgriffith.wordpress.com/events/soft-carp/)
    - [Hacky Hour](https://hackyhourgriffith.wordpress.com)
    {% endcapture %}

{% include card.html header="Ways to get help at Griffith" text=text %}

-->
---

{% capture text %}
    **All done here?** Head to the [next page](4-writing.html) or [ask a question](https://griffithu.padlet.org/y_banens1/60je7s1g90b3f69h){:target="_blank"}. 
    {% endcapture %}

{% include alert.html text=text color="success" %}
