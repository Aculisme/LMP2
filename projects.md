---
layout: page
title: Projects
permalink: /projects/
# remove once "/ is finished being developed
# redirect_from:
#   - /
---

## Papers

#### **Extended Essay in Physics: Solar Optimization**

For my International Baccalaureate Extended Essay in Physics I chose to investigate the optimum positioning of a solar panel located in Geneva Switzerland. My research question was: _"What is the optimal tilt angle of a fixed-position polycrystalline photovoltaic solar panel located in Geneva, Switzerland with respect to maximum annual energy generation?"_.  
Links: [Full paper](/assets/EEV8.pdf)
<br>

#### **Higher Level Maths Internal Assessment: Numerical Methods**

For my Maths Internal Assessment I wrote a paper exploring three common numerical methods and their applications, as well a theoretical investigation and empirical benchmarking of their efficiencies.<!-- in zero-finding and root-solving.--> <!-- I compared the Bisection method, Newton's method, and Secant method in terms of their rate & order of convergence and potential breakpoints. I also implemented the algorithms in Python and wrote a set of benchmarking scripts compare how long each took to converge on a known root. -->
Links:
* [Full paper](/assets/Maths_IA_Luca_Mehl.pdf)
* [Github repo of scripts created](https://github.com/Aculisme/zero_algorithms)  
<br>

#### **Higher Level Physics Internal Assessment: Solar Internal Resistance**

This paper explored the effect of irradiance on the internal resistance of a photovoltaic cell.
Links:
* [Full paper](/assets/Physics_IA_-_Luca_Mehl.pdf)
<br>

#### **Chemistry SL Internal Assessment: Iodination of Propanone Reaction**

For my Chemistry Internal Assessment I experimentally determined the activation energy of the iodination of propanone reaction.  
Links: [Full paper](/assets/Chem_IA_-_Luca_Mehl.pdf)
<br>

---

## Projects

#### **Network Analysis Version 14 (NV14)**

A project attempting to accurately visualize social structures within my year group. The only input is 'friendships' according to a poll conducted by 5 students in my year group. Nodes inputted into [Gephi](https://gephi.org), modelled with Yifan Hu Proportional model, and converted to website format with help from a Gephi plugin.  
Languages: `JavaScript` `Java` `SQL`  
Links: [NV14](https://nv14.netlify.app)
<br>

#### **Network Analysis Version 18 (NV18)**

A follow-up project of NV14, featuring updated friendships (accurate in Oct 2018) from a larger pool (100 students) and a more efficient edge generation methodology. Made with Gephi, modelled with Force Atlas 2, and available as downloadable images (currently).  
Languages: `PHP` `SQL` `Git`  
{% include image-gallery.html folder="/uploads/projects/nv18" %}
<br>

#### **Sign-in Project**

A 6-month project to develop a late-slip dispenser and software, created in response to students' frustration with the previous late arrivals sign-in system, which required them to wait on line to fill out a slip of paper, making them even later for class.  
With the new system, students scanned their ID card with a barcode scanner, would be registered as late on a database, and a receipt printer would print a late-slip for them to bring to their teacher.
Despite a complete working product, the school was unable to give access to the student database. The project ended up acting as a proof-of-concept, and subsequently a catalyst for the school to contract a company to install a fully-fledged sign-in system with sliding doors and RFID.  
Languages: `CSS` `HTML` `PHP`  
Links: [Landing page](https://nationsdesign.org/projects/signin/index.html) | [Directory](https://nationsdesign.org/projects/signin/search.html) | [Sign-in page (password protected)](https://nationsdesign.org/projects/signin/protected/signin.html)
<br>

#### **Portable Weather Data Logger (PWDL)**

This project was completed for my Personal Project (International Baccalaureate), and inspired by my uncle & aunt, a climate scientist & wildlife biologist, who perform dozens of measurements every hour on their research trips in the Peruvian Andes. My Weather Logger is designed to save them time while they focus on their field activities, being able to record the many different atmospheric conditions, log them in a human-readable document, map them (with GPS) perpetually, and with minimal input from the users.
Equipped with: GPS, barometer, altimeter, hygrometer, thermometer, UV sensor, external water temperature probe.  
Languages: `C++`  
Links:  

* [Ski trip GPS recorded with PWDL](https://ski-week-2018.netlify.com)
  * [Google Earth visualization of GPS coordinates](https://drive.google.com/drive/u/0/folders/18qPdKE13OEDq5m5JjcpnLSmEQ4eEzc-F)
* [Duke of Edinburgh's International Award silver level trip recorded with PWDL](https://ia-silver-route-2018.netlify.com)
<!-- * [Photos of PWDL](https://imgur.com/a/p59KwQB) -->
{% include image-gallery.html folder="/uploads/projects/pwdl" %}
<br>

#### **MEAI (MemeEconomy Artificial Intelligence)**

Collaboration with 3 students (two from UK, 1 from Germany) to create a [Reddit](https://reddit.com) bot. Uses database logging, tensorflow, python reddit API (PRAW).  
Languages: `Python`  
Version control: `Git` | `Bitbucket`  
Links: [Homepage](https://meai.ml)
<br>

#### **Raspberry Pi Home Server**
<!-- TODO: REPLACE THIS PROJECT WITH THE PIHOLE / WEBSITE HOST -->
A Raspberri-pi -based home server running Ubuntu Server, which can be controlled using SSH/SFTP on the LAN *or* externally, via portforwarding. 

#### **Custom event ticketing software**

Every year my school meets with the other two campuses to participate in (and organize) the Bal des Neiges, a winter ball. Every year it attracts 400+ students to each of the two nights (Juniors and Seniors). As part of the Student Council, I was among those responsible for organizing this event. And as the most tech-savvy among our campus's student council (to the best of my knowledge), I was tasked with developing a solution to ticketing at the door.  
I designed tickets to be used across all three campuses and had them printed at a local print-shop. Then, I worked with a younger student from Coding Club to quickly develop a website that could be used to verify that the tickets were valid, mark them as activated, and check whether they had already been used. This system worked so well, with an average of 2 seconds or less to check in each ticket (compared to 20 seconds previously), that it will be used across all three campuses in future years.  
Languages: `HTML` `PHP` `CSS` `SQL`  
Links: [Check-in page for organizers (password protected)](https://nationsdesign.org/projects/bdn/test/index.php)
{% include image-gallery.html folder="/uploads/projects/bdn" %}
**UPDATE:** I went back and re-wrote the whole website, frontend and backend. The website is  hosted on my home web server and I also purchased 3 additional barcode scanners. The software + barcode scanners is now being rented to future Student Councils.
Links: [NEW scanning page for organizers (password protected)](https://lmp.internet-box.ch/bdn)
{% include image-gallery.html folder="/uploads/projects/bdn20" %}
<br>

#### **ManageBac grades extractor**

A web scraping tool that extracts grades from [Managebac](https://cdn.managebac.com) and can analyse them in a dashboard window.  
Languages: `PHP`  
Version control: `Git` | `Bitbucket`  
Links: [MB Scraper](https://nationsdesign.org/projects/signin/MB_scraper/F/index.html)

#### **Coding Club**

Since my school doesn't offer formal coding classes, I decided to start the Coding Club with two friends of mine. I recruited roughly 12 students and taught them the fundamentals of website building, including JS, HTML, and CSS. I also acted as a mentor for students in younger grades working on coding projects for school. 

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

## Other projects

#### **Drip Irrigation System**

## Upcoming Projects

* GUI, dashboard, and analysis for PWDL  
* Permanent weather station