![](https://i.imgur.com/iywjz8s.png)


# Collaborative Document 2025-04-03 Reproducible research through reusable code workshop

Welcome to The Workshop Collaborative Document.

This Document is synchronized as you type, so that everyone viewing this page sees the same text. This allows you to collaborate seamlessly on documents.

----------------------------------------------------------------------------


This is the Document for today: https://edu.nl/7fba9

##  🫱🏽‍🫲🏻 Code of Conduct

Participants are expected to follow these guidelines:
* Use welcoming and inclusive language.
* Be respectful of different viewpoints and experiences.
* Gracefully accept constructive criticism.
* Focus on what is best for the community.
* Show courtesy and respect towards other community members.
 
## ⚖️ License

All content is publicly available under the Creative Commons Attribution License: [creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

## 🙋Getting help

To ask a question, just raise your hand.

If you need help, place a pink post-it note on your laptop lid. We will come to assist you as soon as possible.

## 🖥 Workshop website

* [Workshop website](https://esciencecenter-digital-skills.github.io/2025-04-03-repro-essb/)
* [Workshop assignment](https://esciencecenter-digital-skills.github.io/reproducible-research-through-reusable-code)


## 👩‍🏫👩‍💻🎓 Instructors
Sven van der Burg, Eduard Klapwijk

## 👩‍💻👩‍💼👨‍🔬🧑‍🔬🧑‍🚀🧙‍♂️🔧 Roll Call
Name/ pronouns (optional) / job, role / social media (twitter, github, ...) / background or interests (optional) / city



## 🗓️ Agenda
* 09:30 Welcome & icebreaker
* 09:45 Workshop introduction: why is reproducibility important?
* 10:15 Software dependencies
* 10:30 break
* 10:40 Software dependencies continuation
* 11:00 Software documentation
* 11:30 break
* 11:40 Code conventions and modular coding
* 12:30 Lunch
* 13:30 Next steps: how to make your code reusable?
* 13:45 Work on your own project
* 15:00 break
* 15:10 Reusability check
* 16:15 Wrap-up
* 16:30 DRINKS


## 🏢 Location logistics
* Coffee and toilets?
* In case of an emergency
* **Wifi**: Eduroam should work.
    * If it doesn't work, there is a WiFi day code that you can use:
        * SMS the keyword: 82eur
        * To phone number: +316 3574 4774

## 🎓 Credits
For graduate schools. Email e.klapwijk@essb.eur.nl

## 🧠 Collaborative Notes
### Dependencies exercise
1. Which version do you expet to be easiest to re-run? Why?
2. What problems do you anticipate in each solution?

Write your name and your answer:



### Good and bad examples of documentation
* Think of projects with good documentation. What do you like about them?
* Think of projects with less good documentation. What don't you like about them? Are you missing anything?

NB: You can choose a mature library with lots of users, but try to also think of less mature projects you had to collaborate on, or papers you had to reproduce.
#### good:
- pandas: good user documentation, versioned documentation, clear function/class names, large community :panda_face: :panda_face: :panda_face::panda_face: :panda_face:
- pydantic (https://docs.pydantic.dev/latest/)
  - Pretty
  - Lots of examples 
- plumemodel (Internal use only :sad_face: )
    - Very well documented with examples
- Geopandas
- [Luxor.jl](juliagraphics.github.io/LuxorManual/stable/)
    - Consistently puts utilities in contextual examples
-Decent dataset integration
- Seaborn (https://seaborn.pydata.org/)
 - Interactive
- [fmriprep](https://fmriprep.org/en/stable/index.html) > very extensive, lots of examples


#### bad:
- pulp: no step by step explanation of how all components work, mostly shows "case studies" (some small examples) that are not generalizable to different ways of using the library
-
-
-
-
-
-

### Reproducibility check
We will now check the reproducibility of someone else's project!
1. Write down the link to your coding project and the programming language below.
2. Write down your name behind a link if you start reviewing the reproducibility, try to pick a project that is not being reviewed yet.
3. Open a Github issue with your findings

#### List of projects:
- https://github.com/mbraakhekke/geopearl-eu2 ; Input data available here: https://filesender.surf.nl/?s=download&token=a21b2587-7590-40ac-9238-26288c926b0e 
- https://github.com/g-adel/Alluvial ; Python
- https://github.com/GiuliaMelanie/FD-response-times ; Python (notebook)
- https://github.com/ManuelLeeuwerik/eScience_workshop/ : R and in project_example/workflow also a Snakefile (full workflow)
- https://github.com/zaf-tno/SLS ; Python 
- https://github.com/FrancienVeenman/lf_curas_reproducible_code_course ; R 
- https://github.com/Q-uinta/Contribution-analysis/tree/main; Python 
- https://github.com/wolke-wanderer/reproducible_code ; Python 


## Feedback :speech_balloon: 
Please give us some feedback about this morning, so we can tailor the workshop to your needs in the afternoon and improve it for next time it is taught. Think about the pace, the content, the learning environment.

### What went well :+1:
- Online info and assignments are clear and nicely interactive +1
- The pace of the workshop is really good
- It's really nice that the material is open source and there's a lot of nice extra information (external links) that I will surely look at after the workshop
- Great to be actively working on it while being able to ask questions.
- Good to include both R and Python examples
- Low barriers to entry to join the worksop
- Very nice to have coffee, tea and lunch :)
- I like the setup with the collaborative document!
- Nice documentation, clear instructions and great that Phyton and R are included

### What can be improved :-1: 
- The written information is sometimes limited (everything is documented, but in some cases it goes through the steps quite fast/skips some basic information) 
- It was only by chance that I discovered there was a prepratory assignment the evening before, advertising this more clearly might help having everybody well prepared.
- Specify more clearly that the code we should bring to the course will be shared with others.
- It would be nice to show in the workshop how to make virtual environments
- Perhaps we could start with documentation before the dependencies as that part was done quickly for some and it would've been nice to be able to go back and do more documentation
- An example project file could be shared beforehand
- What is expected as an end project is not completely clear, could maybe be given as an example before the course starts, so participants can think ahead what type of code to bring, or what they want to achieve during the course as an end product. 

### Sven's summary
- TODO for us:
    - Add information about virtual environments
    - Improve instructions in assignment
    - Add example projects
        - Maybe a few of your projects?
- How can we make it more clear:
    - that there is a pre-workshop assignment
        - Put it in the title of the email
        - Put it on eventbrite
        - Put it everywhere
- Quickstart template for README file


## Post-workshop survey
Please fill in the [post-workshop survey](https://www.surveymonkey.com/r/GZ35FCK)

## 📚 Resources
- templates:
    - https://github.com/NLeSC/python-template
    - https://cookiecutter-data-science.drivendata.org/
- https://www.makeareadme.com/
- https://book.the-turing-way.org/communication/communication

