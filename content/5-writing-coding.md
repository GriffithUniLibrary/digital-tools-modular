## Coding <span class="fas fa-rocket"></span> 

{% capture text %}
Plain text editors are much more important than you might think. Get yourself a good one.
{% endcapture %}
    
{% include alert.html text=text color=info %}

{% capture editors %}
These text editors are all oriented towards programming and editing code. They have features that are helpful when working in code, like syntax coloring and code folding. Even if you don't consider yourself a programmer, you'll find a good text editor invaluable.

- **[Sublime Text](https://www.sublimetext.com)**: one of the most popular programming text editors for Windows

- **[Notepad++](https://notepad-plus-plus.org/)**: a popular free option

- **[BBEdit (Mac)](https://www.barebones.com/products/bbedit/)**: a venerable (30y+) program with many fans.

- **[Atom](https://atom.io)**: Free, extensible with lots of plugins

- **[Brackets](http://brackets.io)**: Adobe's free text editor.

- **[Visual Studio Code](code.visualstudio.com)**: Microsoft's programming-oriented text editor. Free and highly extensible. 

{% endcapture %}
{% include card.html header="<i class='fas fa-superscript'></i> Programming text editors" text=editors %}

{% capture besttext %}
**Our recommendation: Visual Studio Code**

Microsoft's editor is free, highly extensible (meaning it has lots of plugins to improve its features) and integrates directly with GitHub. I'm writing these words in VS Code right now!
{% endcapture %}
{% include alert.html text=besttext color="primary" %}

### Markdown editors

{% capture aboutmarkdown %}
`Markdown` is a simple and popular text formatting syntax. It has many advantages for writing for the web, including the fact that it produces plain text files, which are easily shared. It's worth becoming familiar with it. This site is written in Markdown.
{% endcapture %}
{% include alert.html text=aboutmarkdown color="info" %}

{% capture markdowntools %}
All of the programming text editors above support Markdown. Below are some dedicated Markdown editors. 

- **[Dillinger](https://dillinger.io)**:  popular and free online Markdown editor.
- **[Stackedit](https://stackedit.io)**: popular and free online Markdown editor.
- **[Ulysses](https://ulysses.app)**: a general-purpose writing app with good Markdown support.
- **[Marked 2 (Mac)](https://marked2app.com)**
{% endcapture %}
{% include card.html header="<i class='fab fa-markdown'></i> Markdown editors" text=markdowntools %}

{% capture text %}
**What's a development environment?**: It's a set of tools that allow you to write, debug, build and run code. Some development environments support a single language  or platform (like R), and some (like Visual Studio) support multiple languages and platforms.
{% endcapture %}

{% include alert.html text=text color="info" %}

{% capture environments %}
- **[R](https://www.r-project.org)**:  extensible, support through Hacky Hour and Carpentries
- **[Python](https://www.python.org)**: support through Hacky Hour and Carpentries
- **[GitLab](https://gitlab.rcs.griffith.edu.au)**: Griffith University shared code repository
- **[Visual Studio](https://visualstudio.microsoft.com)**: mulitiplatform IDE published by Microsoft
- **[GitHub](https://github.com)**: a popular code repository site. This site is hosted on GitHub.
- **[Anaconda](https://www.anaconda.com/distribution/)**: Python development environment
{% endcapture %}

{% include card.html header="<i class='fas fa-bug'></i> Development languages and environments" text=environments %}

{% capture programminghelp %}
**Ways to get help at Griffith:**
- [Software carpentry](https://hackyhourgriffith.wordpress.com/events/soft-carp/)
- [Hacky Hour](https://hackyhourgriffith.wordpress.com)
{% endcapture %}
{% include alert.html text=programminghelp color="info" %}