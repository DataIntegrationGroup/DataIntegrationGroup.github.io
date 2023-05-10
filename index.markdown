---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

[DIG](/) | [About](/about/) | [Data](/data/) | [Software](/software/) | [Contact](/contact/)

## Welcome to the Data Integration Group

Our core purpose is to improve the flow of data from producer to consumer. We develop, implement, and maintain
software solutions that enable the Bureau of Geology to efficiently and effectively manage and disseminate data.


## Vision

![nmgrl_datasharing_vision.png](docs/assets/images/nmgrl_datasharing_vision.png)




## News

{% for post in site.posts %}
{{ post.date | date: "%B %-d, %Y" }}: [{{ post.title }}]({{ post.url }})
{% endfor %}