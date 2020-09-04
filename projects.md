---
layout: page
title: Projects
permalink: /projects/
---

*[Papers](#papers)* | 
*[Projects](#projects)*  

## Papers

#### **★ Extended Essay in Physics: Solar Optimization**

For my IB Extended Essay in Physics I chose to investigate the optimum positioning of a solar panel. My research question was: _"What is the optimal tilt angle of a fixed-position polycrystalline photovoltaic solar panel located in Geneva, Switzerland with respect to maximum annual energy generation?"_.  
Links: [Full paper](/assets/EEV8.pdf)
<br>

#### **★ Higher Level Maths Internal Assessment: Numerical Methods**

For my Maths IA (Internal Assessment) I wrote a paper exploring three common numerical methods and their applications, as well a theoretical investigation and empirical benchmarking of their efficiencies.<!-- in zero-finding and root-solving.--> <!-- I compared the Bisection method, Newton's method, and Secant method in terms of their rate & order of convergence and potential breakpoints. I also implemented the algorithms in Python and wrote a set of benchmarking scripts compare how long each took to converge on a known root. -->
Links: [Full paper](/assets/Maths_IA_Luca_Mehl.pdf) | [Github repo of scripts created](https://github.com/Aculisme/zero_algorithms)  

#### **★ Higher Level Physics Internal Assessment: Solar Internal Resistance**

This Physics IA paper explored the effect of irradiance on the internal resistance of a photovoltaic cell.
Links: [Full paper](/assets/Physics_IA_-_Luca_Mehl.pdf)  

#### **Chemistry SL Internal Assessment: Iodination of Propanone Reaction**

For my Chemistry IA I experimentally determined the activation energy of the iodination of propanone reaction.  
Links: [Full paper](/assets/Chem_IA_-_Luca_Mehl.pdf)  

---

## Projects
<!-- {% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
{% endfor %} -->
{% for post in site.posts %}
<b><a href="{{ post.url }}">{{ post.title }}</a></b>
{{ post.excerpt }}
{% endfor %}

## Upcoming Projects

* GUI, dashboard, and analysis for PWDL  
* Permanent weather station
