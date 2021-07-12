### Statistical analysis

{% capture text %}
The boundaries between qualitative and quantitative tools are becoming blurred. Some tools are specific to certain fields or use cases. [Seek methodological advice](https://www.griffith.edu.au/research/research-services/researcher-education-development/statistical-advice) before you start!
    {% endcapture %}

{% include alert.html text=text color="warning" %}


{% capture outofscope %}
**Note:** an explanation of how these tools work is beyond the scope of this workshop.
{% endcapture %}

{% include alert.html text=outofscope color="info" %}

{% capture quant %}
 - **[SPSS](https://www.griffith.edu.au/student-computing/available-software)**: Griffith provided, limited support

  - **[SAS](https://www.griffith.edu.au/student-computing/available-software)**: Griffith provided, no support.

 - **[Matlab](https://www.mathworks.com/products/matlab.html)**: available through some departments

 - **[STATA](https://www.stata.com/)**
 
 {% endcapture %}

{% include card.html header="<i class='fas fa-sort-amount-down'></i> Quantitative analysis" text=quant %}

{%- capture otherstats -%}
There are potentially other types of applicaiton that are not yet identified. 
{%- endcapture -%}

{%- include otherstats -%}