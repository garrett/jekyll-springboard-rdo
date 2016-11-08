---
title: "Red Hat Community"
layout: default
index: false
class: frontpage intro
---

{% capture intro %}
RDO is a community of people using and deploying OpenStack on CentOS, Fedora, and Red Hat Enterprise Linux.

[Try RDO Now →](/install/quickstart/){:.button}
{% endcapture %}


{% capture try %}
## Try it

Try out OpenStack in one of three ways:

1. Deploy a production cloud with the [TripleO Quickstart.](/tripleo)  
2. [TryStack.org](http://trystack.org)lets you try OpenStack with your own applications in our sandbox environment.  
3. Spin up an all-in-one concept cloud with the [All-In-One Quickstart.](/install/quickstart)
{% endcapture %}


{% capture join %}
## Join the conversation

The conversation happens in several places:

- On the [mailing lists](/community/mailing-lists)
- #RDO on the Freenode IRC network
- [ask.openstack.org](http://ask.openstack.org)
{% endcapture %}


{% capture hack %}
## Hack on it

There are different ways to get involved:

Help out with [packaging](/documentation/rdo-packaging/)one of the OpenStack projects.

Tackle one of the [open issues](http://tm3.org/rdobugs)or[review](http://review.rdoproject.org)a pending changeset.

Check out the [current status](http://dashboards.rdoproject.org)of the project.
{% endcapture %}


{% capture involved %}
## Get involved

{:.lead}
RDO project is made of people like you! If you want to help out, [here's how](/community) you can get involved.

If you are interested in our community, please have a look at our [Code Review process](https://review.rdoproject.org/) and follow the discussion on the [RDO mailing list](https://www.redhat.com/mailman/listinfo/rdo-list)where the discussion covers topics like installing, running, and using OpenStack on Red&nbsp;Hat based distributions.

Want to update this documentation? Great! All you need is a GitHub account, then visit the link at the very bottom of each page, entitled "Edit this page on GitHub".

There are many ways to [get involved](/community/) with the RDO community once you [get started](/install/quickstart/) — the simplest way is to [head over to the ask.openstack.org forum](http://ask.openstack.org) and help answer questions.

The Puppet modules used in packstack are on [GitHub](https://github.com/packstack)and packstack itself is on [Stackforge](https://github.com/stackforge/packstack). For a commercially-supported enterprise ready OpenStack solution, Red Hat provides [Red Hat OpenStack Platform](http://access.redhat.com/products/red-hat-openstack-platform/) — an enterprise-class cloud platform based on OpenStack.
{% endcapture %}


{% capture whatis %}
## What is RDO?

![An Openstack Distribution](/images/wiki/Openstack-distribution.png?1460046750)

RDO is a community of people using and deploying OpenStack on CentOS, Fedora, and Red Hat Enterprise Linux. We have [documentation to help get started](/documentation/), [mailing lists](/community/mailing-lists/) where you can connect with other users, and [community-supported packages](/install/quickstart/) of the most up-to-date OpenStack releases available for download.

If you are looking for enterprise-level support, or information on partner certification, Red Hat also offers [Red Hat OpenStack Platform](//redhat.com/en/technologies/linux-platforms/openstack-platform).

OpenStack relies on the underlying operating system and hypervisor — and what better operating system to build on than the industry's leading enterprise operating system? The RDO community is your one-stop community site for all things related to using OpenStack on Red Hat based platforms.
{% endcapture %}


{% capture happening %}
## What's happening?

Come to one of the main [events](events) where some of us will be. Follow us on [Twitter](http://twitter.com/rdocommunity/), [Facebook](http://facebook.com/rdocommunity), and [Google+](https://plus.google.com/communities/110409030763231732154). Subscribe to the [rdo-list mailing list](http://www.redhat.com/mailman/listinfo/rdo-list) for technical questions, or to the [newsletter mailing list](http://www.redhat.com/mailman/listinfo/rdo-newsletter) for monthly community updates.

{:.social-icons}
- [Events](/events/)
- [Mailing list](https://www.rdoproject.org/Mailing_lists)
- [Twitter](http://twitter.com/rdocommunity)
- [Facebook](http://facebook.com/rdocommunity)
- [Google+](https://plus.google.com/communities/110409030763231732154)
{% endcapture %}

{% comment %}
FYI: Mardkdown doesn't like being rendered within HTML tag blocks, 
so we have to resort to using HTML snippets below
{% endcomment %}

<div class="intro">
  <div class="intro-stack"></div>
  <div class="intro-text">{{ intro | markdownify }}</div>
</div>

<div class="grid">
  <div class="col-4">{{ try | markdownify }}</div>
  <div class="col-4">{{ join | markdownify }}</div>
  <div class="col-4">{{ hack | markdownify }}</div>
  <div class="col-6">{{ involved | markdownify }}</div>
  <div class="col-6">{{ whatis | markdownify }}</div>
  <div class="col-12">{{ happening | markdownify }}</div>
</div>
