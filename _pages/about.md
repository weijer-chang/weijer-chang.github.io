---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I recently completed my Ph.D. at UC Berkeley in the [Mechanical Systems Control Lab](https://msc.berkeley.edu/), affiliated with [BAIR](https://bair.berkeley.edu/) and [Berkeley DeepDrive](https://deepdrive.berkeley.edu/), advised by Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/) and Dr. [Wei Zhan](https://zhanwei.site/).
I am supported by the NSF Graduate Research Fellowship Program and the Taiwan–UC Berkeley Fellowship.

My research focuses on developing safe and intelligent autonomous systems for complex, human-centered environments. Central to this work are machine learning, generative models, and reinforcement learning with applications in autonomous driving and robotics. A key aspect is to tackle challenges involving multi-agent, interactive human behavior and complex long-tail scenes at scale.


Currently, I’m on [Tesla AI](https://www.tesla.com/fsd)’s Autopilot team, working on Full Self-Driving (FSD) to contribute to real-world autonomy.
Previously, I was a research intern at [Applied Intuition](https://www.appliedintuition.com/), where I worked on large-scale, human-like self-play reinforcement learning, and at [NEC Labs](https://www.nec-labs.com/) with [Manmohan Chandraker](https://cseweb.ucsd.edu/~mkchandraker/#), focusing on language-based, safety-critical simulation for autonomous driving.

I graduated from National Taiwan University. I worked in [Bio-Inspired Robotics Lab](http://biorola.me.ntu.edu.tw/members_alu_ms.html) as an undergrad researcher, advised by Prof. [Pei-Chun Lin](https://scholar.google.com/citations?user=KdWMoM4AAAAJ&hl=en), we developed a [Spherical Robotics System](https://www.youtube.com/watch?v=TvrreooQh-I) that with hybrid rolling and leaping capability.

# News

{% include news-list.html %}

# Publications

For the most up-to-date list of publications, please see [google scholar]({{site.author.googlescholar}}).

<style>
  .pub-table { width:100%; max-width:800px; margin:1.5rem auto; border-collapse:separate; border: none; }
  .pub-table .thumb-cell { width:180px; padding:0 20px 20px 0; vertical-align:middle; border: none; }
  .pub-table .thumb-cell img, .pub-table .thumb-cell video { width:100%; height:auto; display:block; border-radius:4px; }
  .pub-table .text-cell { padding-top:4px; vertical-align:middle; border: none; }
  .pub-title { font-size:1.1rem; line-height:1.35; font-weight:bold; }
  .pub-authors, .pub-venue { font-size:0.9rem; margin:0.25rem 0; }
</style>

{% for pub in site.data.representative_publications %}
  {% include pub-item.html
     title=pub.title
     authors=pub.authors
     venue=pub.venue
     year=pub.year
     paper=pub.paper
     website=pub.website
     code=pub.code
     blog=pub.blog
     image=pub.image
     video=pub.video %}
{% endfor %}
