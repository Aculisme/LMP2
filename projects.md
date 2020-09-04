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
Links:
* [Full paper](/assets/Maths_IA_Luca_Mehl.pdf)
* [Github repo of scripts created](https://github.com/Aculisme/zero_algorithms)  
<br>

#### **★ Higher Level Physics Internal Assessment: Solar Internal Resistance**

This Physics IA paper explored the effect of irradiance on the internal resistance of a photovoltaic cell.
Links:
* [Full paper](/assets/Physics_IA_-_Luca_Mehl.pdf)
<br>

#### **Chemistry SL Internal Assessment: Iodination of Propanone Reaction**

For my Chemistry IA I experimentally determined the activation energy of the iodination of propanone reaction.  
Links: [Full paper](/assets/Chem_IA_-_Luca_Mehl.pdf)
<br>

---

## Projects
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>
{% endfor %}

#### **School Social Media Directory**

Summer coding project to make a directory of all the new (and old) students in the grade.  
Languages: `HTML` `SCSS` `JS`  
Links:  

* [Social Media Directory](https://nationsdesign.org/projects/nv15/directory.php?year=12)
* [Screen shots](/assets/social_media_directory_landing_page.png)

#### **Reddit image extractor script**

An image scraper for Reddit that extracts up to 1000 images from a target subreddit and stores them in a local folder.  
Languages: `Python`  
Links: [reddit image scraper](https://github.com/aculisme/reddit-image-scraper)  

#### **Portfolio website**  

This website is hosted by Netlify, deployed from [Github](https://github.com/Aculisme/LMP) using Docker, and created using the [Jekyll](https://jekyllrb.com) static website generator.
Languages: `Git` `Markdown` `html/css`  

#### **ASCII converter bot**

Originally a simple programming exercise, this project is now so large that it is best described as two separate parts:

1. An efficient and novel media converter from any video format into a gif/video created from only ASCII characters.
2. A Reddit bot created using PRAW which can be 'summoned' to convert a video submission into its ASCII equivalent. [unfinished]  
Languages: `Python`  

## Upcoming Projects

* GUI, dashboard, and analysis for PWDL  
* Permanent weather station