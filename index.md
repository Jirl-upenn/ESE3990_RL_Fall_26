---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: "Reinforcement Learning: In Theory and In Practice"
---

# Reinforcement Learning: In Theory and In Practice
Fall 2026. ESE 3990. Tue / Thu 10:15-11:45. DRLB 3C4

![Image](/assets/images/front-page.png)

## Announcements 
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Course Overview 

This course provides a comprehensive treatment of reinforcement learning, bridging the gap from classical foundations in dynamic programming and optimal control to the cutting edge of modern AI. Students will explore how agents learn optimal behaviors in possibly uncertain and partially observable environments. We will start from simple MDP and Bandit games and gradually build towards high-dimensional state spaces using deep neural networks for function approximation. Towards the end of the course, we will cover case studies in autonomous robotics and the fine-tuning of large language models (RLHF). At the end of this course, students will be equipped to use RL solutions for advanced applications and critically evaluate their performance, advantages, and limitations against alternative optimization methodologies.


### Prerequisites

This is a undergraduate-level course. Students are expected to have prior knowledge in linear algebra and geometry. Prior experience with deep learning will be beneficial but not necessary.


## Schedule 

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructors

<figure style="display: inline-flex;">
<figure>
<img src="assets/images/al.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://antonilo.github.io/"><button type="button" name="button" class="btn">Antonio Loquercio</button>
</a></figcaption>
</figure>

</figure>

## Teaching Assistants

<figure style="display: inline-flex;">
<figure>
<img src="assets/images/chunwei.png" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://xingcw.github.io/"><button type="button" name="button" class="btn">Chunwei Xing</button>
</a></figcaption>
</figure>

</figure>


<!-- ## Teaching Assistants 

<figure style="display: inline-flex;">

<figure>
<img src="/real_world_robot_learning_sp25/assets/images/lmk.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://www.linkedin.com/in/leonmkim/"><button type="button" name="button" class="btn">Leon Kim</button>
</a></figcaption>
</figure>

<figure>
<img src="/real_world_robot_learning_sp25/assets/images/js.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://junyaoshi.github.io/"><button type="button" name="button" class="btn">Junyao Shi</button>
</a></figcaption>
</figure>

</figure> -->

## Related Courses


Deep Reinforcement Learning: <a href="https://cmudeeprl.github.io/403website_s25/"> CMU version</a> <a href="https://rail.eecs.berkeley.edu/deeprlcourse/"> UC Berkeley version</a>.

<a href="https://davidstarsilver.wordpress.com/teaching/"> Reinforcement Learning </a>, UCL. (The foundation part of our course is heavily based on this material).



