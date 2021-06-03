{% capture surveys %}

{% include card.html header="<i class='fas fa-paperclip'></i> Reference management software" text="[Get advice from a qualified statistician](https://www.griffith.edu.au/research/research-services/researcher-education-development/statistical-advice) before you design and deploy your survey. They will help you understand the impact your survey and question design will have on the final data output." %}

{% capture text %}

 - [Lime Survey](https://prodsurvey.rcs.griffith.edu.au/doco2/) is Griffith's supported survey tool. It is fast, flexible and free. [Workshops](https://www.griffith.edu.au/research/research-services/researcher-education-development/workshop-calendar) and [video resources](https://www.youtube.com/playlist?list=PLOtTT7TqB2izC3THIFCokfIh5DwlOPePH) are available too.
 - [RedCap](https://www151.griffith.edu.au/redcap/) is also free and Griffith-supported. It is better suited to clinical and longitudinal studies. Training resources are still under development. 

{% endcapture %}
{% include card.html header="Recommended options" text=text %}

 
{% capture text %}
These options are popular, but don't come with any support from the University. 

 - [Google Forms](https://docs.google.com/forms/)
 - [Microsoft Forms](http://forms.office.com)
 - [Survey Monkey](https://www.surveymonkey.com)
 - [Qualtrics](https://www.qualtrics.com) is popular in psychology. Griffith no longer holds a license so it will not be free for you to use.
{% endcapture %}
{% include card.html header="Other options" text=text %}

{% endcapture %}
{% include card.html header="<i class='fas fa-paperclip'></i> Reference management software" text=surveys %}