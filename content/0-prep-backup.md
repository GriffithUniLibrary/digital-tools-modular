## Where will your precious data live?

{% capture ftf %}
**First things first:** 
    
Find a place to put your research data. Don't lose it. Keep it secure.
{% endcapture %}
{% include alert.html text=ftf color=primary %}

Your data storage location is critical. It needs to be three things: reliable, secure, and backed up. 

### Reliability

{% include modal.html button="What do you mean by 'reliability'?" color="info" title="About reliability" text="Reliability means there's a very low chance that the medium you've recorded your data on will fail. Modern computer hard drives are fairly reliable, but they still can fail. Laptop hard drives in particular can be less reliable." %}

It's much better for reliability to entrust your data storage to a cloud provider. Cloud providers host data on servers with 'failover redundancy', meaning if one server ever fails, another is ready to take its place instantly. This is how they can advertise '99.999% uptime'. 

{% capture options %}
- [Cloudstor](https://cloudstor.aarnet.edu.au) is powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.
- [Google Drive](https://www.google.com/drive/)
- [OneDrive](https://griffitheduau-my.sharepoint.com/)
- [Dropbox](https://www.dropbox.com/)

{% include card.html header="🔄 Online storage & sync" text=options %}

{% capture note %}
**Note:** When signing in to OneDrive, be sure to use your Griffith credentials rather than a personal Microsoft account.
{% endcapture %}
{% include alert.html text=note color="info" %}{% endcapture %}


{% capture cloudstor %}Our recommendation: AARNet Cloudstor

[Cloudstor](https://cloudstor.aarnet.edu.au) is powered by AARNet (The Australian Academic Research Network) and provides students and researchers with a Terabyte of free, ultra-fast storage. It's easy to set up and works just like Dropbox.
{% endcapture %}

{% include alert.html text=cloudstor color=info %}

{% include video-embed.html youtubeid="mGaqxrrxfgA" caption="Signing in to Cloustor" %}

### Security

### Backups

This is where we talk about backups. 

{% include alert.html text="**Warning** Hello, this is an alert" color=primary %}