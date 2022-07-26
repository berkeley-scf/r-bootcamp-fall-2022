# UC Berkeley R Bootcamp, August 2022

This is the website for the tenth annual R bootcamp at Berkeley. The bootcamp will be an intensive two-day introduction to R using RStudio, held all day on Saturday August 20 and Sunday August 21, 2022

See below for information on [registration](#registration), [logistics](#logistics---when-where-and-how), [workshop content](#preparing-for-the-course---course-content), and [preparing for the workshop](#preparing-for-the-course---software-installation) (primarily installing software in advance.

Sponsored by: UC Berkeley Statistics and the Statewide Database at Berkeley Law

## Overview

The bootcamp will be an intensive two-day introduction to R using RStudio. Topics will include:

 * R basics - reading and manipulating data, working with R data objects, doing calculations
 * R graphics, focused on ggplot
 * programming in R
 * doing data analysis / data science / statistical work in R
 * more advanced topics: efficiency, object-oriented programming, batch jobs, parallel processing

## Prerequisites

The workshop doesn't assume any specific R knowledge and starts from the very basics, but it goes at a fairly quick pace (hence *bootcamp*). This is appropriate for:

 - Those with some (but not necessarily much) R experience who want a refresher, want to take their skills to the next level, or want to see a holistic presentation of what's possible in R.
 - Those with some experience in another language (e.g., Python, MATLAB, C/C++, Java) who would like an introduction to R.
 - Those who are incoming Statistics or Biostatistics graduate students to UC Berkeley.
 - Those will little or no R experience (or other programming experience) who think they are likely to be able to keep up with the pace. If so, you should look through the first few modules (Modules 1-3, to be presented Saturday morning) to get a feel for the nature of the bootcamp. You should play around with R some in advance of the workshop, as discussed [below](#preparing-for-the-course---course-content).

In prior years, we've had two tracks, with one track serving to provide a slower pace for those with no experience with R or other programming languages. Unfortunately, this year we do not have staffing to support two tracks.

If you have no R experience and little programming experience in other languages, you are likely to find the pace too quick. Therefore we recommend that you attend one of the [D-Lab](https://dlab.berkeley.edu)'s R Fundamentals workshops. In particular there will be [a workshop the week of August 15](https://dlab.berkeley.edu/events/more-d-lab-events-and-workshops-coming-soon/2022-08-15) (the week before classes start) as well as workshops later in the semester. 

## Registration

Before registering, please check the [prerequisite information](#prerequisites).

To attend you must [submit a registration request](https://forms.gle/pzhSxhc3rCgqubdE7). Submitting the request does not guarantee as spot. Priority will be given to Berkeley grad students, postdocs, staff, and faculty, followed by those affiliated with another university or government agency, then Berkeley undergrads, and finally participants from for-profit organizations. Undergraduates interested in R should consider taking Statistics 133 or Statistics 132. 

NOTE: registrations will only be processed periodically, so there may be a delay in hearing back from us about whether you are registered or on the waitlist.

## Cancellation

If you have registered and realize you cannot attend, PLEASE [cancel your registration](https://forms.gle/Q75qCFDqygL8oY3D6) so that we can let people on the wait-list attend. If you don't cancel, you'll deprive someone else of a spot, as we always have a wait-list for this event.

## Logistics - when, where, and how

Physical location: UC Berkeley campus, building and room TBD.

Time: 
  - Saturday, August 20, 8:15 am - 5 pm
  - Sunday, August 21, 9 am - 4:30 pm

We'll start formally on Saturday morning at 8:30 am, but please plan to get here by 8:15 so you can sign in and get settled. And if you need help with any software installation please come at 8 am.

Here is the [schedule for the bootcamp](schedule) including links to all the modules.

Note that street parking in Berkeley near campus on Saturdays is generally subject to two hour limits.

You will probably want to [make sure you can use the campus WiFi (EduRoam)](https://berkeley.service-now.com/kb_view.do?sysparm_article=KB0013807) in advance of the event. But if you need wireless access as a guest (i.e., you don't have a CalNet ID), connect to 'CalVisitor'.


## Health information

Vaccination requirements will follow [campus requirements](https://uhs.berkeley.edu/requirements/covid19), so essentially everyone should be vaccinated. In particular, those of you arriving from another country should carefully examine these requirements, which will determine if you can attend the bootcamp in person.

## Preparing for the course - course content

WARNING: This material is under construction, with various (but not huge) edits to the content expected. We'll be making edits up until a few days before the event.

Course content is available through GitHub. Please download a copy of the course materials before arriving at the bootcamp using one of the two options below (if you're familiar with Git you'll also know how to do this by cloning the repository):

 1. Via GitHub in RStudio:
    - Open RStudio. 
    - Go to “File→New Project” and select “Version Control” and “Git”. 
    - Enter 'https://github.com/berkeley-scf/r-bootcamp-fall-2022' as the “Repository URL” and click “Create Project” (you can choose the directory in which to place the project with the “Create project as subdirectory of” option). 
    - It should create a “r-bootcamp-fall-2022” directory with all of the materials within whichever directory you chose. 
    - To open one of the R Markdown files, go to the lower right panel, click on 'Files', then 'r-bootcamp-fall-2022', then 'modules' and finally click on the .Rmd file of interest. It will open in the upper left panel.

  2. Alternatively, simply download a zip file containing all the content at https://github.com/berkeley-scf/r-bootcamp-fall-2022/archive/main.zip.

We recommend that you take a look at the [schedule for the bootcamp](schedule) and the [background module](modules/module0_induction) in advance to get a sense for what we'll cover. And for those of you with no experience with R, it will help with your learning curve if you play around some with R using the material in [Module 1](modules/module1_basics) beforehand. Alternatively, if you have absolutely no experience with R or similar languages (e.g., Python, MATLAB), you might check out [Swirl](https://swirlstats.com).

For the presentation materials (including embedded demo code), see the html files in *modules*. The main files have individual pages/slides, while the *_onepage_* html files are one continuous page per module. To run the demo code, open the .Rmd file for the module in RStudio. You can then run individual chunks of code.

## Preparing for the course - software installation

Please come with a fully-charged laptop (Mac, Windows, or Linux are all ok) with R, RStudio, and Git installed. RStudio and Git are optional but highly recommended. 

To install the software, it's best if you can install software directly on your laptop.

  - Install the following directly on your laptop:
  
      - R [(details here)](install/RandRStudioInstall)
      - RStudio (optional but highly recommended) [(details here)](install/RandRStudioInstall)
      - Git (optional but recommended for obtaining course content) [(details here)](install/gitInstall)

Alternatively, IF INSTALLING ON YOUR LAPTOP FAILS, the following is an alternative way to access R and RStudio through a browser:

  - Please use your CalNet ID and password to [login to the Berkeley DataHub](https://r.datahub.berkeley.edu). Once logged in, you should be in an RStudio session in the browser. At this point you can get a copy of the bootcamp files that your RStudio session can access by following instruction #1 above under the section "Preparing for the course - course content".

Note that our ability to troubleshoot R or RStudio installed directly on your machine is limited (particularly in Windows). We'll try to help, but if we run into roadblocks, we'll direct you to the browser option.

## Course Discussion

Please ask questions both during the presentations and during the breakout sessions. 

- Questions can be asked to the presenter or to the circulating bootcamp assistants.
- We'll have an online discussion forum through Ed Discussion for online discussion and answering questions during (and before) the bootcamp.

## Logistical Questions

If you need to contact us directly with an administrative question, you can email r-bootcamp@lists.berkeley.edu.
