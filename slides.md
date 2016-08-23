class: center, middle

### **Doing Data Science (for Social Good)**
## **In academia**

### Ariel Rokem

<image src="images/eScience_Logo_RGB_PP.png">

<small>Follow along at: <a href="">arokem.github.io/2016-08-25-DSSG</a></small>

???

Hello! My name is Ariel Rokem, and I am a data-scientist at the University of Washington eScience Institute. Today, I am going to tell you about the future and what we are doing at the eScience Institue to make research at the University of Washington future-proof.

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>

---

### Doing Data Science

???

In more and more research, future advances depend on our ability to record, process, analyze, and understand large, heterogeneous, noisy data. On the one hand, these are exciting times, in which we look forward to a near future in which data will be able to address many important societal challenges.


On the other hand, the data-intensive future poses some tremendous challenges.

--

Data Science is about extracting actionable insights from large heterogeneous noisy data

???

In this presentation, I will tell you aout the eScience Institute, and I will tell you how we are working at the eScience Institute to future-proof data-intensive discovery, by developing the role of data science at the University, and beyond.

--



???
What does that mean?

--

   - Catalyzing collaborations

???

Much of our work capitalizes on unique opportunities to collaborate across disciplines.

--

   - Building and maintaining the tools

???
We believe that the future requires new tools for discovery, and we are building these tools. Even more importantly, we are creating the conditions for these tools to survive and to thrive.

--

   - Sustaining career paths in data-intensive research

???
One of the main challenges that we face as individuals, and also as an organization is sustaining careers at the interesection of tool-building and research. The eScience Institute provides a career path for data scientists like myself to pursue these important avenues, and also serves as a laboratory to experiment with what these career paths might look like.

--

   - Training data-savvy researchers

???
Finally, the topic of this session, and a focus of much of our energy is an investment in education and the training of a future generation of data-savvy researchers.

In this talk, I will discuss all of these challenges and provide you a glimpse into some of the work we are doing at the eScience Institute to secure a future-proof environment for data-intensive research.

But first, let me set the stage by telling you a little bit about my own career trajectory...
---

### Who am I?
--

<image src="images/huji-logo.png" height=100px> I am originally from West Jerusalem, Israel

???
I come from West Jerusalem, in Israel. In college, at the Hebrew University, I studied Biology and Psychology. This education provided a basis for my interest in interdisciplinary work and for graduate school...
--

<image src="images/berkeley-logo.png" height=100px> Ph.D. In neuroscience

???
...I came to the United States, and studied, at the University of California, Berkeley
--

<image src="images/stanford-logo.png" height=100px> Research experience in computational neuroimaging

???
After graduate school, I spent a few years conducting research in computational neuroimaging, as a post-doc at Stanford.
--

 <image src="images/scipy-logo.png" height=100px> <image src="images/nipy-logo.png" height=100px> Open source software development

???
In graduate school, I started developing open-source software for computational neuroimaging, and became part of a community called "NIPY" (or neuroimaging in Python), which uses the Python programming language to develop open-source tools for analysis of data from human neuroimaging.

---

### Neuroimaging is data-intensive!

<video id="mri-zstack" preload="auto" width="85%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/mri-zstack.mov"/></video>

???
Neuroimaging data, here showing a human brain scanned with an MRI machine at millimeter resolution, can provide detailed information about the structure and function of an individual human brain.

These data provide some amazing opportunities

---

### Doing Data Science in academia: the data deluge

--
Across many different fields

???

This data deluge is not unique to neuroscience
--

Astronomy

???
Other fields, like astronomy...
--

Genetics

???
...and genetics, have been dealing with large data sets for many years.

What is unique at this time is that this data deluge is now affecting many more fields, some of whom have never been
--

...

--

Social sciences

???
One example are fields in the social sciences. Where some questions could once be answered by collecting responses in a survey, many researchers can now turn to large data-sets at the scale of entire societies.

--
<image height="25%" src="images/cell-phone-poverty.jpg">

Josh Blumenstock

???
For example, in this research from I-School researcher Josh Blumenstock and his group, high resoltion maps of poverty and wealth in an entire country (In this case, the central-African country Rwanda) can be generated based on cell-phone usage patterns

---

### The eScience Institute

<image src="images/eScience_Logo_PMS.png" height=150px>

???

The mission of the University of Washington eScience Institute is to collaborate with researchers across disciplines, to develop and apply advanced computational methods and tools to ask interesting and important questions amidst this data deluge.
--
<p>
</p>
<image src="images/DSE-and-sponsors.png" height=200px>

$ 37.8M for 5 years: <a href="http://msdse.org/">"Moore-Sloan Data Science Environments"</a>

???
We have a broad portfolio of funding from many sources, but a major source of support is a grant that we got a few years ago from the Moore and Sloan foundations. The funding from these foundations has created a collaborative network of environments at three institutions: NYU, Berkeley and The University of washington, devoted to data science.


### Challenges for DS in academia:

???
In academia, on the other hand, data science presents several challenges. These challenges are the focus of our work, and form the main working groups that the Moore-Sloan effort is funding
--

- Tools and software

???
The first is the development of tools and software for
--

- Reproducibility and open science

???
A second challenge that faces science that depends on an intensive engagement with data is the challenge to make this research open and reproducible.
--

- Career paths for data scientists

???
Faced with compelling opportunities in the private sector, academia is challenged to retain and nurture the careers of individuals with the combination of skills needed to pursue data-science.
--

- Education and training

???
It is almost equally challening to provide training and education to a new generation of data-driven researchers, in the face of rapidly developing tools and systems, and within the confines of traditional academic disciplinary silos.
--

- Physical and intellectual space

???
One of the solutions to this problem is the creation of physical and intellectual spaces that provide the setting for work on . More about that in just a minute.

--

- Data Science studies

???
Similarly, we are interested in distilling the lessons we are learning about data science in academia. For this purpose, researchers in the eScience Institute are conducting ethnographic studies, and a working group on data science studies is conducting explorations aimed to understand what facilitates success in academic data science. This group is also exploring the complex ethical implications of data science.

---

### Tools and software

Connecting research on data science methodology (Computer Science and Engineering, Statistics, Applied Math) with domain research questions.

???
A major part of the work that we do is to develop tools and software that will be useful to researchers in a variety of fields. This means that we connect work in data science methodology, such as computer science, statistics, and others, with work in specific domains.

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

Computer Science: Magda Balazinska, Alvin Cheung, Parmita Mehta, Sven Dorkenwald

<image src="images/myria-logo.png">

Astronomy: Andy Connoly, Jake Vanderplas

Biology: Dave Williams

???

Magda Balazinska and others on the Computer Science and Engineering department have developed systems for cloud computing data analysis, such as the Myria system. Our current work together builds upon this expertiese to build together the next generation of scientific image processing tools, that will serve researchers across all of these domains, and more.
---

### The challenge of novelty squared

<a href="https://medium.com/@profjsb/novelty-squared-dd88857f662#.j9jtwaxe9">Josh Bloom</a>:

"the challenge of finding work that may be simultaneously novel both to the domain scientist and to the core computation, statistical, and algorithmic scientist. "

???
This kind of research poses a particular kind of challenge, because both sides of the collaboration have to be interested in it. This is what Josh Bloom, an astrophysicst from our collaborating institute at Berkeley has called "The challenge of novelty squared"

--

“The last thing I want to have happen with an interdisciplinary collaboration is that my CS and stats colleagues find their contribution to be routine if not mundane.”

???

Living in the future has its downsides! This work will not produce a neuroscience paper in the immediate future. Instead, it might produce the systems that all neuroscientists will use in 5 years!

So - while novelty squared is hard, it is also potentially transformative!
---

### The challenge of reproducibility

Reproducibility is a bed-rock of the scientific method.

--

As data and computations become more elaborate, it's not enough to describe you did.

--

#### Show your work!

???
As I mentioned before, one of the challenges for DS is that as the data and computations become more elaborate, a simple verbal description of the procedures will not suffice.

Instead, one way to restore the trust in the reproducibility of the work is to conduct our research in a manner that is transparent and open.
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem1.png" height=500px>

???

We all rely on the Python language itself
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem2.png" height=500px>

???

Over the years, people have developed excellent tools in Python to support basic computational tasks that are common across many fields. For example, a library called numpy supports numerical operations on multi-dimensional arrays of data, such as those in image data.

Another library called scipy supports a wide range of computations, signal processing, statistics, optimization, and so forth.
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem3.png" height=500px>

???
On top of these basic tools, others have built tools that support a variety of domain agnostic operations: machine learning, plotting, symbolic math, etc.

---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem4.png" height=500px>

???
Finally, researchers in various domains

Part of what makes this ecosystem so powerful is the fact that information flows in both directions: researchers at the edges, in various domains rely on the central projects, such as numpy and scipy, but they also contribute back to the development of these projects, allowing everyone to enjoy the network effect of an open and collaborative development community.
---

### Doing Data Science for Social Good (in academia)

Addresses two additional challenges:

???

Another form of our incubator projects is our Data Science for Social Good Program (or DSSG). This program addresses two major challenges.
--

How do we provide training for data-scientists interested in social good?

???
The first is the education of data-scientists, especially in the social sciences, and fields that pertain to social good
--

How do we enable data-driven approaches in institutions devoted to social good?

???
The other is our ability to provide solutions to "real-world" problems outside the university.

---

### The future is already here

--

### ... it's just not very evenly distributed.
                                              (William Gibson)

???

... the future is already here (click). It's just not very evenly distributed.

--

  - Catalyzing collaborations

--

  - Building and maintaining the tools

--

  - Sustaining career paths in data-intensive research

--

  - Training data-savvy researchers

---
class: center
layout: false

### Stay in touch!

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
