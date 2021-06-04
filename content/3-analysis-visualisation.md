## Data visualisation

{% capture text %}
No matter what tool you use, you'll need a little bit of training to make good data visualisations. RED offers workshops on [data visualisation and data storytelling](https://app.secure.griffith.edu.au/events/category/developing-researcher-training-program). The Library has also produced an [online introduction](https://sway.office.com/O9vEKmTmBXPxGOnE) you might find useful.
{% endcapture %}
{% include alert.html text=text color="info" %}

{% capture dataviz %}
- **[Data to Viz](https://www.data-to-viz.com/)**: Helps you to decide which type of graph is appropriate to your data. 

- **[Tableau](https://public.tableau.com)**: academics and students have access to the full desktop version (see the [Tableau Gallery](https://public.tableau.com/en-us/s/gallery) for some great inspiration)

- **[RAWGraphs](https://app.rawgraphs.io)**: Free and open source, secure browser-based visualisation (you can also run it locally, i.e. outside of a browser). Intended to 'bridge gap between spreadsheet applications and graphics editors'. Version 2.0 beta is available.

- **[PowerBI](https://powerbi.microsoft.com)**: Connects well with other Microsoft data sources but costs money to use.

- **[Prism](https://www.graphpad.com/scientific-software/prism/)**

- **[Chart.js](https://www.chartjs.org)**: Simple yet flexible JavaScript charting for designers & developers. 
{% endcapture %}

{% include card.html header="<i class='fas fa-eye'></i> Data visualisation tools" text=dataviz %}

{% capture bestdataviz %}
**Our recommendation: Tableau**

Tableau can produce beautiful results quickly and is free to academic researchers. It's not supported by the University, but neither are any of the others. 
{% endcapture %}

{% include alert.html text=bestdataviz color="primary" %}


<script>
  // === include 'setup' then 'config' above ===
{% include_relative chart.md %}
{% include_relative demo-chart.html %}

  var myChart = new Chart(
    document.getElementById('myChart'),
    config
  );
</script>

Activity: Want to try out some data visualisation? Of course you do!

{% include button.html text="Go to the Tableau activity" link="activity-tableau.html" color="info" %}
