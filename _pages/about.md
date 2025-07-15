---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a final-year Ph.D. student at UC Berkeley in the [Mechanical Systems Control Lab](https://msc.berkeley.edu/), affiliated with [BAIR](https://bair.berkeley.edu/) and [Berkeley DeepDrive](https://deepdrive.berkeley.edu/), and advised by Prof. [Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/) and Dr. [Wei Zhan](https://zhanwei.site/). 

My research focuses on **behavior simulation for autonomous driving**. Central to this work are machine learning, generative models, reinforcement learning, and robotics. A key aspect is to tackle challenges involving multi-agent, interactive human behavior and complex long-tail scenes at scale.

# Publications {#publications}

For the most up-to-date list of publications, please see <a href="{{site.author.googlescholar}}">google scholar</a>.

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
     image=pub.image 
     video=pub.video %}
{% endfor %}
