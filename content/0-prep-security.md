___

### Security

{% capture text %}The best way to keep your passwords *different and secure* is to use a password manager. ⭐️ The best *password* to use is a *passphrase*.{% endcapture %}
{% include alert.html text=alert color="info" %}

### <i class="fas fa-key"></i> Password managers

Getting used to using a password manager is a great investment in your overall experience of using the Internet. Most password managers have browser plugins that can fill login forms automatically. 

{% capture text %}
You could, but you would be missing out on a few of the key benefits of password managers, like checking that your passwords aren't being reused across services, generating new passwords for you and syncing your passwords across mobile and desktop devices.
{% include figure.html img="ch-preparation.png" alt="A boy and his tiger look out to the distance" caption="Preparing to embark" width="75%" %}
{% endcapture %}
{% include modal.html button="Why can't I just let my browser remember my passwords?" color="info" title="Why not save in a browser" text=text %}


{% capture pwmanagers %}
 - **[LastPass](https://www.griffith.edu.au/passwords/lastpass)**: Griffith's supported password manager. It is available to all staff. 
 - **[Bitwarden](www.bitwarden.com)**: free and open source, multiplatform, simple to use. Very modern and well-regarded.
 - **[1Password](https://1password.com)**: high quality commercial (paid) option. It's been around along time and has a good reputation.
 - **[Dashlane](https://www.dashlane.com)**
{% endcapture %}
{% include card.html header="Password managers" text=pwmanagers %}

{% capture pwrecommended %}
**Our recommendation: Bitwarden**

Although LastPass is offered by Griffith, it is not as seamless as Bitwarden, and does not necessarily come with you if you leave Griffith. For that reason, we recommend going with Bitwarden. 
{% endcapture %}
{% include alert.html text=pwrecommended color="primary" %}