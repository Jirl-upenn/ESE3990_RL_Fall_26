---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: Physical Intelligence: Foundation and Systems 
---

# Physical Intelligence
Fall 2025. ESE 6510. Tue / Thu 10:15-11:45. Fagin Hall 118.

![Image](/assets/images/front_page.png)

## Announcements 
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Course Overview 

Why don't we yet have a foundation model that can operate robots in the physical world? What makes applying the standard pre-training approach so uniquely challenging in robotics? And what recent advances are pushing the boundaries of what’s possible in real-world applications?

This course offers a structured framework to explore these questions. We will study the mathematical foundations of techniques for learning-based decision-making and examine how these methods are deployed in robotic systems. Through a combination of lectures, hands-on projects (including a drone race!), and guest presentations from leading experts in the field, students will gain a deep understanding of the state-of-the-art decision-making systems and their challenges when applied to robotics.

### Prerequisites

This is a graduate-level course. Students are expected to have prior knowledge in deep learning and robotics, such as the topics covered in Robot Learning (ESE 650), Applied Machine Learning (CIS 5190), and Introduction to Robotics (MEAM-520).


## Schedule 

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructors

<figure style="display: inline-flex;">
<figure>
<img src="/real_world_robot_learning_sp25/assets/images/al.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://antonilo.github.io/"><button type="button" name="button" class="btn">Antonio Loquercio</button>
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

<a href="https://robots-that-learn.github.io/"> Robots that learn</a>, UC Berkeley.

<a href="https://manipulation.csail.mit.edu/index.html"> Robotics Manipulation</a>, MIT.

Deep Reinforcement Learning: <a href="https://cmudeeprl.github.io/403website_s25/"> CMU version</a> <a href="https://rail.eecs.berkeley.edu/deeprlcourse/"> UC Berkeley version</a>.

<a href="https://16-831-s24.github.io/"> Introduction to Robot Learning</a>, CMU.

<a href="https://abajcsy.github.io/embodied-ai-safety/">Embodied AI Safety</a>, CMU. This course is not only very interesting, but also has an awesome webpage.



