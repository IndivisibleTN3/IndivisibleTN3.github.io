---
layout: default
---

Welcome! We are Indivisible TN3, a Signal Mountain, TN group opposing the Trump agenda. We are following this playbook to achieve our policy goals and make our voices heard:

[The Guide][guide]

It was written by former Congressional staffers and provides a strategy for having maximum impact through contact with our US senators and representative.

If you'd like to join us, you can find us on [Facebook][fb], or join our [Discussion Group][group].

[guide]: https://www.indivisibleguide.com
[fb]: https://www.facebook.com/indivisibletn3/
[group]: https://groups.google.com/forum/#!forum/IndivisibleTN3


## [](#blog)Posts

{% for post in site.posts %}

#### [{{ post.title }}]({{ post.url }})

*{{ post.date }}*

{{ post.excerpt }}[...]({{ post.url }})

{% endfor %}