---
layout: people
background: /assets/images/kaist.jpg
title: Minseong Jang (장민성)
excerpt: "Minseong Jang's website"
---

{%- assign person_id = "minseong.jang" %}
{%- assign person = site.data.people | where:"id",person_id | sample %}

<img align="right" style="width: 30%; padding-left: 3%;" src="{{ site.baseurl }}/assets/images/people/minseong.jang.jpeg" alt="{{ person.name }}">

I am an **Undergraduate Student at [Mathematical Science](https://mathsci.kaist.ac.kr) and [KAIST School of Computing](https://cs.kaist.ac.kr)**.
I am interested in designing concurrent and parallel systems.

I am currently working on [FPGA high-performance networking systems]({{ site.baseurl }}{% link _projects/fpga.md %}).

{% include person_contact.md person_id=person_id %}

{% include person_education.md person_id=person_id %}

#### Experiences

- Software Engineer, Waddle Corporation, April, 2019 - January, 2021.
  
  (topic: Back-end development, R&D)
