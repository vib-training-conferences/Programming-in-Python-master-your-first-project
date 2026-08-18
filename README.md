<!--
author:   name last_name
email:    trainingandconferences@vib.be
version:  2.0.0
language: en
narrator: UK English Female

icon:     https://vib.be/sites/vib.sites.vib.be/files/logo_VIB_noTagline.svg

comment:  This document shall provide an entire compendium and course on the
          development of Open-courSes with [LiaScript](https://LiaScript.github.io).
          As the language and the systems grows, also this document will be updated.
          Feel free to fork or copy it, translations are very welcome...

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
link:     https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
link:     https://raw.githubusercontent.com/vib-tcp/material-liascript/master/img/org.css
link:     https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css
link:     https://fonts.googleapis.com/css2?family=Saira+Condensed:wght@300&display=swap
link:     https://fonts.googleapis.com/css2?family=Open+Sans&display=swap

link:  https://raw.githubusercontent.com/vib-tcp/material-liascript/master/vib-styles.css

@edition:  1st 
@CourseTitle: replace by course title

import:   https://raw.githubusercontent.com/vib-tcp/training_material_template/refs/heads/main/macro.md

-->
# Gentle Hands-on Introduction Programming

Teaching materials for the course. This course is intended to help new
programmers find their feet and begin them on their journeyto writing
useful programs.

Lesson overview
-----------------

> <i class="fa fa-lock"></i> **License:** [Creative Commons Attribution 4.0 International  License](https://creativecommons.org/licenses/by/4.0/deed.en)
>
> <i class="fa fa-user"></i> **Target Audience:** Anyone who whant to get started with Python
>
> <svg xmlns="http://www.w3.org/2000/svg" height="14" width="16" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.--><path d="M384 64c0-17.7 14.3-32 32-32H544c17.7 0 32 14.3 32 32s-14.3 32-32 32H448v96c0 17.7-14.3 32-32 32H320v96c0 17.7-14.3 32-32 32H192v96c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32h96V320c0-17.7 14.3-32 32-32h96V192c0-17.7 14.3-32 32-32h96V64z"/></svg> **Level:** Beginner  
>
> <i class="fa fa-arrow-left"></i> **Prerequisites**  
>
> This course is designed for participants with **NO** prior programming experience
> 
> <i class="fa fa-bookmark"></i> **Description**  
> Do you want to learn programming skills that will boost your research? In this course, we introduce you to the Python programming language, starting from the very basics. You will explore core programming concepts through a mix of live online sessions, guided practical afternoons, and self-paced exercises. We emphasize hands-on learning in a supportive environment where you can ask plenty of questions. By the end of the course, you will be able to read, modify, and write Python programs and feel confident continuing with more advanced programming topics.
> 
> <i class="fa fa-arrow-right"></i> **Learning Outcomes:**  
>
> By the end of the course, learners will be able to:
>
> 1. Understand core programming concepts including functions and values
> 2. Analyze programs written by peers to understand their structure and logic 
> 3. Modify existing programs to improve functionality or adapt them to new tasks
> 4. Develop new programs to solve practical problems 
> 5. Apply techniques to detect errors and fix problems in code 
>
> <i class="fa fa-hourglass"></i> **Time estimation**: 40 h
> * 4 half days Q&A 
> * Self-study time
>
> <i class="fa fa-asterisk"></i> **Requirements:** 
>
> No installation is required previously. You need to register to the course to get access to [Dodona](https://dodona.be/), the platform where the course will be offered. Find the [next course](https://www.vibtrainingandconferences.be/events?text=master+your+first&f%5B0%5D=status%3Aupcoming) and register now.
>
> <i class="fa fa-envelope-open-text"></i> **Course Materials**:
> 
> 1. The material is available in this repository and in Dodona (_under registration_) 
>
> ## Proposed Schedule
>
>> | Once a week: | Self-study, everyday |
>> | :---         | :---                 |
>> |  14:00 to 17:00 - Q&A |   2h a day  |
>
> <i class="fa fa-life-ring"></i> **Acknowledgement**:
>
> * [ELIXIR Belgium](https://www.elixir-belgium.org/)
> * [VIB Technologies](https://www.vib.be/)
>
> <i class="fa fa-money-bill"></i> **Funding:**
> - This project has received funding from VIB.
>
> <i class="fa fa-anchor"></i> **PURL**:  <span style="color:red">not yet available</span>
>
>
> ## Authors and Contributors
>
> Authors
>
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0002-0020-421X) James Collier
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](http://orcid.org/0000-0000-0000-0000) Nina Buchina
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0002-3926-7293) Tuur Muyldermans
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0002-9226-0103) Frank Vernaillen
>
> Contributors
>
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0002-6958-6498) Tatiana Woller
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0001-5958-0669) Bruna Piereck
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0009-0007-1722-2370) Janick Mathys
> 
> [<img src="https://raw.githubusercontent.com/vib-training-conferences/training_material_template/refs/heads/main/docs/images/ORCID-iD_icon_vector.svg" width="20"/>](https://orcid.org/0000-0003-2179-0366) Jolan Heyse
>
> ## Citing this lesson
>
> Please cite as:
>
> 1. <span style="color:red">to be updated soon</span>
>

## Workshop and Material organization

> We are using the interactive Open Educational Resource online/offline course infrastructure called LiaScript.
> It is a distributed way of creating and sharing educational content hosted on github.
> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge: [LiaScript](https://liascript.github.io/course/?https://raw.githubusercontent.com/vib-tcp/training_material_template/main/README.md)

## About us

*About ELIXIR Training Platform*

The ELIXIR Training Platform was established to develop a training community that spans all ELIXIR member states (see the list of Training Coordinators). It aims to strengthen national training programmes, grow bioinformatics training capacity and competence across Europe, and empower researchers to use ELIXIR's services and tools.

One service offered by the Training Platform is TeSS, the training registry for the ELIXIR community. Together with ELIXIR France and ELIXIR Slovenia, VIB as lead node for ELIXIR Belgium is engaged in consolidating quality and impact of the TeSS training resources (2022-23) (https://elixir-europe.org/internal-projects/commissioned-services/2022-trp3).

The Training eSupport System was developed to help trainees, trainers and their institutions to have a one-stop shop where they can share and find information about training and events, including training material. This way we can create a catalogue that can be shared within the community. How it works is what we are going to find out in this course.

*About VIB and VIB Technologies*

VIB is an entrepreneurial non-profit research institute, with a clear focus on groundbreaking strategic basic research in life sciences and operates in close partnership with the five universities in Flanders – Ghent University, KU Leuven, University of Antwerp, Vrije Universiteit Brussel and Hasselt University.

As part of the VIB Technologies, the 12 VIB Core Facilities, provide support in a wide array of research fields and housing specialized scientific equipment for each discipline. Science and technology go hand in hand. New technologies advance science and often accelerate breakthroughs in scientific research. VIB has a visionary approach to science and technology, founded on its ability to identify and foster new innovations in life sciences.

The goal of VIB Technology Training is to up-skill life scientists to excel in the domains of VIB Technologies, Bioinformatics & AI, Software Development, and Research Data Management.

--------------------------------------------

*Editorial team for this course*

Authors: @[orcid(Alexander Botzki)](https://orcid.org/0000-0001-6691-4233), @[orcid(Bruna Piereck)](https://orcid.org/0000-0001-5958-0669)

Technical Editors: Alexander Botzki

License: [![CC BY SA](images/cc-by-sa.png)](https://creativecommons.org/licenses/by-sa/4.0/deed.en)

```json   @JSONLD
{
  "@context": "https://schema.org/",
  "@type": "LearningResource",
  "@id": "https://elixir-europe-training.github.io/ELIXIR-TrP-TeSS/",
  "http://purl.org/dc/terms/conformsTo": {
    "@type": "CreativeWork",
    "@id": "https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE"
  },
  "description": "TeSS, how can I help you? This is our interactive hands-on course about efficient use of the ELIXIR TeSS platform.",
  "keywords": "FAIR, OPEN, Bioinformatics, Teaching, TeSS",
  "name": "TeSS, how can I help you?",
  "license": "https://creativecommons.org/licenses/by/4.0/",
  "educationalLevel": "beginner",
  "competencyRequired": "none",
  "teaches": [
    "search events and material in TeSS via direct and faceted search",
    "add manually and automatically events and material to TeSS",
    "extract events and material from TeSS by using TeSS widgets"
  ],
  "audience": "training providers",
  "inLanguage": "en-US",
  "learningResourceType": [
    "tutorial"
  ],
  "author": [
    {
      "@type": "Person",
      "name": "Bruna Piereck"
    },
    {
      "@type": "Person",
      "name": "Olivier Sand"
    },
    {
      "@type": "Person",
      "name": "Alexander Botzki"
    }
  ],
  "contributor": [
    {
      "@type": "Person",
      "name": "Yasmine Maes"
    },
    {
      "@type": "Person",
      "name": "Finn Bacall"
    },
    {
      "@type": "Person",
      "name": "Munazah Andrabi"
    }
  ]
}
```

## Outline

1. _Introduction_: We begin with [Hedy](https://hedy.org), a _gradual_ introduction to programming. This
   aids in learning to think computationally. But also builds confidence and provides quick
   feedback between writing a program and seeing outp[ut on the screen. Finally, it motivates
   syntax (especially for strings).
2. Data types: introduces the concept and value of types and the Python syntax for data type annotations.
3. Functions: introduces functions as an abstraction for program design and construction.
   Testing is also covered. This chapter forms the final theoretical foundation for the course.
4. Decisions: `if`, `elif`, and `else`.
5. Collections: lists, operations on lists, `in`.
6. Loops: `for`-each loops over lists, stings, and `reange()`.
7. Dictionaries: associating data, looping, slicing, and other operations.
8. Input and output: dealing with the outside world. Data cleaning and some common
   file formats in bioinformatics, such as csv and fasta, are covered.
9. Plotting: a teaser for more advanced topics.


## Hedy

As part of your welcome email you should receive a link to join Hedy. When you click on the link you should see
a website asking if you want to join the class.

![Join a Hedy class](images/hedy_join_class.png)

When you click on the "Join class" button you will be prompted to create an account. Click "Yes".

![Hedy create a account](images/hedy_create_account_dialog.png)

You will then be asked to login using a username and password. If you do not already have an account you can
click on the "Create account" button.

![Create a Hedy account](images/hedy_login_form.png)

You will now be asked if you are a student or a teacher. You should click "Student".

![Hedy question: student or teacher](images/hedy_create_account_step1.png)

At this point you have successfully created your account and joined the class.

![Hedy finished](images/hedy_first_login.png)

