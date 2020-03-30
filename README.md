# brey-bulma-icecast-connector
# Owner
Created by Brian Reyman, originally on March 2020. Stored in GitHub at https://github.com/breyman/brey-bulma-icecast-connector/

# Description
Small include for use with Bulma.io styling and connecting to a live icecast audio/podcast streaming service. Intended for use most easily with Jekyll, but would work well with others as well.

Currently only mean to be embedded at most once on each page.

# Configuration
If using with Jekyll:
* Place directory in your Jekyll \_includes folder.
* Include audio-live-stream.html into project, as desired.
* Create and set the icecast_server_mountpoint variable in the page's front matter that is including the content.

If not using with Jekyll:
* Copy contents of audio-live-stream.html file into your project.
* Replace *{{ site.icecast_server_mountpoint }}* with your specific icepoint server endpoint URL.
