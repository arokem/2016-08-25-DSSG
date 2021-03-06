class: center, middle

### **Doing Data Science **
## **(for Social Good)**
### **in academia**

### Ariel Rokem

<image src="images/eScience_Logo_RGB_PP.png">

<small>Follow along at: <a href="">arokem.github.io/2016-08-25-DSSG</a></small>

???

Hello! My name is Ariel Rokem, and I am a data-scientist at the University of
Washington eScience Institute. In a previous talk, you heard about our DSSG
program. In my talk, I will discuss a few of the challenges that we face in
doing data science in general, and DSSG more specifically within a university
environment. I will also try to offer a couple of promising directions, from our
own experience, and hope to have further discussions about this later in the
day.

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>


---

<image height="70%" src="images/UW-DSSG-venn-diagram.png">

---

### I am trained as a neuroscientist

Neuroscience is data-intensive!

<video id="mri-zstack" preload="auto" width="75%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/mri-zstack.mov"/></video>

???
Neuroimaging data, here showing a human brain scanned with an MRI machine at millimeter resolution, can provide detailed information about the structure and function of an individual human brain.

--

The data deluge provides tremendous opportunities

--

But there are also challenges

---

### Challenges for Data Science in academia

- Data science methodology: computer science, statistics, applied math, etc.

--

- Domain research questions: neuroscience, astrophysics, sociology, etc.

--

<image src="images/pi_shaped.png" height=275px>

Jake Vanderplas:<a href="https://jakevdp.github.io/blog/2014/08/22/hacking-academia/">"Hacking Academia" </a>


???
A major part of the work that we do is to develop tools and software that will be useful to researchers in a variety of fields. This means that we connect work in data science methodology, such as computer science, statistics, and others, with work in specific domains.

---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem3.png" height=500px>

???
On top of these basic tools, others have built tools that support a variety of domain agnostic operations: machine learning, plotting, symbolic math, etc.

---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem4.png" height=500px>

???

Part of what makes this ecosystem so powerful is the fact that information flows in both directions: researchers at the edges, in various domains rely on the central projects, such as numpy and scipy, but they also contribute back to the development of these projects, allowing everyone to enjoy the network effect of an open and collaborative development community.

---

###  
###   
<p>



</p>
<image src="images/DSE-and-sponsors.png" height=200px>

#### <a href="http://msdse.org/">Moore-Sloan Data Science Environments</a>

--

#### Roles for data scientists at the universities

--

#### Plug the <a href="https://jakevdp.github.io/blog/2013/10/26/big-data-brain-drain/">"big data brain drain"</a> to industry

---
### Data Science for Social Good

Addresses challenges:

???

Another form of our incubator projects is our Data Science for Social Good Program (or DSSG). This program addresses two major challenges.
--

The data deluge is having a transformative effect on the social sciences

--

How do we train data-scientists with a strong interest in social sciences?

???
The first is the education of data-scientists, especially in the social sciences, and fields that pertain to social good
--

How do we enable data-driven approaches in institutions devoted to social good?

???
The other is our ability to provide solutions to "real-world" problems outside the university.
--

#### But also creates additional challenges:

--

- How do we select fellows?

--

- How do we elicit and develop compelling projects?

--

- How do we provide technical mentorship?

--

- How do we sustain and maintain the projects we build?

---

#### eScience Data Scientists serve as technical mentors

--

- Help evaluate fellows and projects for selection

--

- Teach the initial "boot-camp" workshops

--

- Provide guidance on technologies and methodologies

--

- Provide day-to-day guidance on workflow and project management

---

#### Data scientists help maintain projects long-term

Family homelessness: factors leading to permanent housing (Summer 2015)

<image height="40%" src="images/PierceTrajectories.png">

<small>
Bill & Melinda Gates Foundation: Neil Roche and Anjana Sundaram

DSSG Fellows: Fabliha Ibnat, Jason Portenoy, Chris Suberlak, Joan Wang
</small>
---

### Continuing the work

--

Data scientists: Bryna Hazelton, Ariel Rokem

--

Graduate students: Kivan Polimis, Kathleen Moore

--

- Build and maintain a set of software tools for ETL of HMIS data from Puget Sound counties

--

- And for applications of machine learning to these data:

  https://scikit-learn-contrib.github.io/forest-confidence-interval

--

- Bring the data and software back to stakeholders in the counties

--

- Develop future summer DSSG projects

---

class: center
layout: false

<div style="position:absolute; left: 220px; top:100px;">
  <img src="images/globe-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">http://arokem.org
  </div>
</div>
<div style="position:absolute; left: 220px; top:220px;">
  <img src="images/email-11-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">arokem@gmail.com
  </div>
</div>
<div style="position:absolute; left: 220px; top:340px;">
  <img src="images/twitter-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">@arokem
  </div>
</div>
<div style="position:absolute; left: 220px; top:460px;">
  <img src="images/github-6-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">github.com/arokem
  </div>
</div>



---

### Image Processing Across Domains

Many research domains use image data!

<video preload="auto" width="60%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/moth.mov"/> </video>

???
For example, we have noticed that researchers at the institute from several different fields all use image data and image processing algorithms in their research. For example, researchers in the biology department use high-speed cameras to record the flight of moths, and analyze these data to better understand how their wings work.
---

### Image Processing Across Domains

Many research domains use image data!

<image src="images/Cepheid-Variable-Stars.jpg">

???
Researchers in astronomy use humongous image data to model the structure of distant galaxies.
---

### Image Processing Across Domains

Computer Science: Magda Balazinska, Alvin Cheung, Parmita Mehta, Sven Dorkenwald, Dongfang Zhang

<image src="images/myria-logo.png">

Astronomy: Andy Connoly, Jake Vanderplas

Biology: Dave Williams

???

Magda Balazinska and others on the Computer Science and Engineering department have developed systems for cloud computing data analysis, such as the Myria system. Our current work together builds upon this expertiese to build together the next generation of scientific image processing tools, that will serve researchers across all of these domains, and more.

---

### The challenge of reproducibility

Reproducibility is a bed-rock of the scientific method.

--

As data and computations become more elaborate, it's not enough to describe you did.

--

#### Show your work!

--

This becomes even harder when the data are sensitive, contain PII...

--

... which is often the case for DSSG projects!


???
As I mentioned before, one of the challenges for DS is that as the data and computations become more elaborate, a simple verbal description of the procedures will not suffice.

Instead, one way to restore the trust in the reproducibility of the work is to conduct our research in a manner that is transparent and open.


---

### The challenge of novelty squared

<a href="https://medium.com/@profjsb/novelty-squared-dd88857f662#.j9jtwaxe9">Josh Bloom</a>: "the challenge of finding work that may be simultaneously novel both to the domain scientist and to the core computation, statistical, and algorithmic scientist. "

???
This kind of research poses a particular kind of challenge, because both sides of the collaboration have to be interested in it. This is what Josh Bloom, an astrophysicst from our collaborating institute at Berkeley has called "The challenge of novelty squared"

Living in the future has its downsides! This work will not produce a neuroscience paper in the immediate future. Instead, it might produce the systems that all neuroscientists will use in 5 years!

So - while novelty squared is hard, it is also potentially transformative!

--
### In many cases, it takes two Γ-shaped researchers

---

### Community-level data science

<small>
Brittany Fiore Gartland and Anissa Tanweer

<a href="http://escience.washington.edu/community-level-data-science-and-its-spheres-of-influence-beyond-novelty-squared/">"Community-level data science and its spheres of influence: beyond novelty squared"</a>
</small>


Daily practices across a network of practitioners

<image src="images/pis_and_gammas.png" height=300px>

---
