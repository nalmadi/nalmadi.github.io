---
layout: post
title: "Tamsin Rogers '23 Building Tools to Understand the Brain at the Child Mind Institute"
author: "Naser"
categories: Interview
tags: [Interview, student]
image: https://nalmadi.github.io/assets/img/Tamsin.jpg
published: true
---
<meta name="image" property="og:image" content="https://nalmadi.github.io/assets/img/Tamsin.jpg">
<sup>One of the best parts about my job is that it has allowed me to experience living and working in NYC. - Tamsin Rogers '23.</sup>
  

This post is part of a spotlight series highlighting the work of exceptional students and alumni.  The series aims to facilitate knowledge sharing on topics such as internships, jobs, entrepreneurship, and graduate school.  


Today, I have the pleasure of talking to Tamsin Rogers '23 about her work and experience as a Technical Specialist at the Child Mind Institute.



**Can you tell us about your work as a Technical Specialist at Child Mind Institute?** 



The Child Mind Institute is a nonprofit organization that is dedicated to transforming the lives of children and families experiencing mental health and learning disorders.  It provides clinical care, research, and advocacy to support children, teens, and young adults struggling with conditions such as anxiety, ADHD, depression, and autism.

I work in the Research department, in the Center for Data Analytics, Innovation, and Rigor (DAIR).  The DAIR team is focused on developing open-source neuroimaging tools that are designed to answer fundamental questions about the brain.  We also conduct computational analyses and experimental techniques of fMRI data to study brain network interactions, with the goal of advancing the scientific understanding of brain function and mental health.  

I have three main duties as a Technical Specialist: user support, documentation, and data processing.  My main focus is contributing to the Configurable Pipeline for the Analysis of Connectomes (C-PAC) project, which is an open-source software pipeline for automated preprocessing and analysis of resting-state fMRI data.  This pipeline is used by researchers around the world to achieve groundbreaking discoveries in the field of neuroimaging.  I am the main point of contact for C-PAC, and provide user support to both external users and internal collaborators while maintaining the platform’s user documentation and general online presence.  

I’m currently working on a documentation “auto-system” that pulls technical information straight from our codebase and displays it neatly in a website that I built from scratch, replacing our pre-existing docs.  This system employs continuous integration (CI) practices, meaning that each time a change is pushed to the main branch of our code, the documentation automatically updates to reflect those changes.  For example, if we alter the order in which a sequence of pre-processing steps runs in a certain pipeline configuration, the documentation page that explains reasoning behind those steps will update as well.

What I love about my role is that I am hands on with every aspect of C-PAC.  I get to contribute to the codebase of the software, while also having continuous conversations with the people who use it the most.  When I’m not working on C-PAC, I also develop and test other high-performance software tools developed by the DAIR center.  This is typically done in collaboration with the software developers who head those projects, so I get to meet a lot of people who work in neuroimaging and computing and learn about what excites them.

My role at CMI has also allowed me to participate in things like hackathons, conferences, and research opportunities.  I was recently involved in a data science competition project with the Women in Data Science group, in which I helped make a series of videos explaining an open-source dataset of ours.  Participants in this competition used my videos as a resource while building fMRI-based predictive models to assess ADHD diagnoses.




**What does a typical day look like for you?**



My days at CMI can really vary, so I’ll speak more to the structure of a typical week.  

On Mondays, I work from home, and always start my week by checking each of our user support channels for new and updated posts.  We have several online forums that questions are posted to, in addition to the emails and direct messages my team receives from both internal colleagues and external collaborators.  I’ve found that taking stock of these on Monday gives me a good idea of the scope of work I’ll have for the rest of the week.  Sometimes, a user’s question is a simple configuration or setup issue, and can be easily answered.  Other times, issues are more complex and require several days to work through.  I’ll often reproduce the issue they are experiencing on my end and work closely with my team to solve it.  If the issue they are experiencing warrants a change to our codebase, I’ll open a Github issue for it.  Because C-PAC is open-source, users can also directly post issues, suggestions, and future functionality they’d like to see to our Github repo.  I use the user inquiries I receive to guide the type of content I include in our documentation.  Things like FAQs and tutorials kind of write themselves when we’re so closely connected to the people who use the product.

On Tuesdays, I go into our Midtown office and have a 1 on 1 meeting with my manager.  We discuss progress I’ve made on the various C-PAC-related projects I’m assigned to and make a plan for the following week.  We also always devote some time to discussing the overarching goals I have set for the year and we can make sure the work I’m doing aligns with those goals.  I have lunch with my team and then attend a weekly meeting of the entire DAIR center, during which I learn about the status of our other ongoing projects.  This is also around the time I’ll kick off any data processing runs I need for the week, which often necessitates writing a handful of new Bash scripts.

I work remotely on Wednesdays, and usually spend that time doing heads-down documentation work.  I find that I write best when I know I have several uninterrupted hours to myself, and since I don’t have any meetings on Wednesdays, this system works pretty well.  

My Thursday mornings and early afternoons are devoted to DAIR-specific meetings.  These meetings are topic-based, and range from things like data engineering and LLM applications to open science outreach and grant writing.  Anyone who is currently working on a project that falls into one of these categories attends that meeting and shares any relevant updates.  I find these meetings to be a good opportunity for collaboration and I always learn something new!  On Thursdays I also write a summary of what I’ve been working on that week and share it with my direct team.  My coworkers do the same, which helps us all better understand what we’ve been prioritizing, what we’ve accomplished, and what we may need a hand with.

Fridays are less meeting-heavy, and I usually devote them to doing quality checks or other assessments of the data I ran earlier in the week.  Since I work with fMRI data, I can open up any scans of interest in a viewer and get a sense of how well the processing went.  Being able to visualize the data is especially useful when my team is doing something like brain masking, where we isolate specific areas of brain tissue for focused analysis.  Sometimes I’ll also kick off more data runs on a Friday so I can report the results back to my team first thing on Monday morning.



**What technologies do you use? And what technologies/languages do you recommend learning today?**



As a Technical Specialist, I mainly use Bash for writing the shell scripts I need to run C-PAC on different datasets.  Due to the large file sizes of the brain scans that go through C-PAC, we rely on high-performance computing (HPC) clusters - specifically, the Pittsburgh Supercomputing Center (PSC) -  to process and store our data.  I’ve learned a lot about storing and working with big data on different servers in this role.

For the automated documentation project, I’ve been doing a lot of content writing in YAML files and then using JavaScript to pull that content into the HTML pages that make up the website.  I also use JavaScript to handle the continuous integration aspect of this project, and since everything is web based, being well versed in HTML/CSS has been helpful.

When working on the actual C-PAC codebase, I’m mainly writing in Python.  C-PAC is based on a Python framework called Nipype, which wraps and standardizes the range of neuroimaging tools that we used for processing raw data, allowing us to create these neuroimaging pipelines and make them both customizable and reproducible.  

Beyond programming proficiency, something I’d recommend in today’s tech world is to get really good at explaining technical processes.  So many people are interested in programming nowadays, but I’m always impressed when someone is able to explain a technical concept in a really engaging, informative way. 


**How does your job align with your academic studies at Colby? Are there specific courses that you found most helpful?**


My Colby CS classes, especially CS333 (Programming Languages), taught me how to build and interact with pipelines and packages, which is something I do every day at CMI.  I also draw on the concepts taught in CS251 (Data Analysis & Visualization) a lot when working with the fMRI data in my role.  I think the most useful class I took at Colby was CS421 (Empirical Software Engineering), which was my senior year seminar with Naser.  This class, by far, taught me the most about how to work with a technical team in a professional setting.  I graduated with a good handle on Git and Agile - skills that are applicable in pretty much any technical role.
In addition to CS at Colby, I also completed a major in Science, Technology, & Society (STS) and a minor in Philosophy.  When I got to CMI, I was equipped with not only the technical knowledge I needed to be successful in my role, but also the writing and presentation skills that are required of me in a communication-heavy position,

Outside of classes, the experience I had as a Colby student that most aligns with my job now was being a research assistant in Naser’s Software Engineering and Human Factors lab.  I joined the lab as a sophomore, and spent the summer of 2021 working with Naser on Namesake - a Python tool that acts as a lexical similarity checker for identifier names used in programming.  Being part of the development of this tool was invaluable - I got to run studies, work with students, publish our findings, and more - I truly owe it to Naser for kick-starting my interest in research.  We even went on to publish papers in the ACM and IEEE during the rest of my time at Colby, and I used Namesake to develop my own biometric eye-tracking tool as part of my senior year thesis.  

I would recommend pursuing (or at least looking into) an honors thesis during senior year.  In addition to participating in focused research and learning on a specific topic, a thesis is a great way to form a close working relationship with a professor, interact with members of your community, and leave Colby with a concrete example of polished, professional work.

My research experience at Colby also helped me realize pretty early on in my career that I’m super interested in working with biometric data and developing related applications.  I’ve found that working in this field allows me to feel that I’m improving the lives of real people in some capacity, and that makes me excited to come into work.  I’m looking forward to further embodying my interests in mental health care and advocacy by using technology for good!



**Can you tell us about the job search and interview process? And how did you prepare for it?**



I graduated in the spring of 2023 and spent my first post-grad summer working in outdoor education in Colorado.  Starting that fall, I worked on a web development team at a non-profit in Boston for about a year, and then moved to NYC.  Being in a new city really inspired me to search for a new role I felt truly passionate about at a company that was doing important work.  I was also working fully remotely at the time and, being new to the city, decided to prioritize finding an in-person experience, in the hopes of being a bit more engaged with my work.  I did all of my job searches on LinkedIn - I find that it’s the most interactive platform for this stuff and I like how easy it is to see if anyone in your network works at a company you might be interested in.  I also found that many additional open positions that didn’t appear in other job boards were often floating around on my feed.

What I value about computer science is that it is applicable in almost any industry.  I have always been interested in working in healthcare tech in some capacity, and got an initial feel of the field as a Healthcare Innovation Intern at Philips (Boston) during the summer before my senior year.  I came across the Child Mind Institute on LinkedIn while researching NYC-based companies focused on mental health, and it seemed like a great match for my interests.  I applied for multiple roles at CMI since I loved the company’s mission so much, and eventually started interviewing with the C-PAC team.  

Since CMI is a nonprofit research organization, the company model is pretty mission-driven and focused on making new scientific discoveries.  In addition to some gentle LeetCode and brushing up on the technical skills that the role I interviewed for required (Unix, Git, Python), I dedicated most of my interview preparation time to researching this mission and studying the work that current CMIemployees had published.  When it came time for my interview, I was ready to discuss exactly how my interests and experience aligned with CMI’s mission, what I was hoping to contribute as a new hire, and the ways in which I wanted to grow at the company in the years to come.

I first had a couple of interviews with the team’s Lead Engineer (now my manager).  I was asked first to describe my technical background, and then we focused on writing/communication skills, experience collaborating/working with teams, and willingness to learn and master new technologies.  I then had the opportunity to interview with the current members of the team, which I found to be the most valuable part of the interview process.  I really got a feel for the dynamic and expectations I would be stepping into - this experience had a pretty big influence on my decision.  



**What tips would you give students interested in joining an organization like the Child Mind Institute? You can mention any details that you like, including websites and other resources.**



It goes without saying that finding a job in tech right now is really challenging.  Keeping myself from feeling discouraged during my senior year job search was really hard.  I felt like I was taking advantage of the resources that were available to me (internships, Colby connections, DavisConnects, etc.), but nothing was panning out the way I thought it would.  My first year of post-grad didn’t really feel perfect either.  I had this idea that after graduating, everything would fall into place the way it should, but I found myself really having to dig a little deeper to figure out exactly the type of thing I would be happy working on once I was out of school.

Something I tried to keep in mind during both of these times was that I was learning.  Obviously, rejections didn’t feel good, but at least the connections I was making were forcing me to get a ton of practice thinking and speaking about who I was, what I was good at, and what I wanted to do.  The research I did on the companies that embodied my areas of interest also helped me craft this idea of an “ideal place” I would want to work at, so that I would know it when I saw it.

I ultimately had better luck getting interview offers from companies that weren’t necessarily “tech companies” at heart, but rather had some kind of internal tech department, even though the company itself may have been in a different industry.  I would recommend applying to roles beyond just ‘Software Engineer’ straight out of college - think outside the box!  In industries that are tech-adjacent (research, consulting, etc.), but don’t have that startup-up coding culture, having a background in CS can really set you apart and be a reason that a team is interested specifically in you as an applicant.

Something else I found valuable about my Colby CS education was that I graduated with a portfolio of programming projects that I could draw on in interviews.  A lot of these projects are included on my resume - with my theses, senior seminar final, and any research I worked on with Naser highlighted.  These are opportunities to prove that you can take ownership of something, which can serve as a great segue for how you will exhibit similar drive at any company you are interviewing for.  I’d recommend including links to anything you might want to discuss in an interview (projects, papers, publications) directly on your resume to make it easy for the recruiter to reference.  Having a list of this stuff also makes it easy for you to quickly respond to questions about your experience level with required technologies for a role!

Now that I’ve been working at CMI for about a year, something I have really come to value about my team is their continued commitment not only to the product we work on, but also all of our personal interests and how they relate to our career goals.  Having such encouraging co-workers is not something I take for granted and has made for a really positive experience at CMI so far.  Because so many of the people I work with have diverse skill sets that go beyond just coding, there is often opportunity to cross-collaborate on projects with people on other teams - something I always hoped I’d be able to do with a technical background.  I would highly recommend taking some time during the interview process to get a feel for the people you will be working with - ask if meeting the team is a possibility!  You can learn more about my team and the work we do at the Child Mind Institute here: [https://childmind.org/science/advancing-methods/dair/](https://childmind.org/science/advancing-methods/dair/).

