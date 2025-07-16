---
layout: page
title: Intro to Programming with MBL
description: A Mastery-based Approach for an Intro to Programming course fostering learning-from-failure (LFF) ideals
img: assets/img/12.jpg
importance: 1
category: pedagogy
related_publications: true
---
This work has been started as a fruit of a KEEN Faculty Development Workshop (<i>Learning From Failure with Mastery-Based Learning</i>) that I was a part of in the summer of 2024. After the workshop, I also received a summer course development grant (summer 2025) to continue with the work.

### Course: 

<p style="text-align: justify;">This is an introduction to programming for Mechanical Engineers, focusing on computer tools that will be used in future classes and their professional careers, mainly Matlab. There is no expectation of prior programming knowledge, so building a strong programming foundation is a key outcome of this class. The use of such computer tools, teamwork skills, and design analysis will be incorporated into several mini-projects throughout the course. </p>
Below is a list of course objectives for ME123. After completing this course, students will be able to: 
•	Write structured programs in Matlab to solve engineering problems. 
•	Create a variety of engineering plots and graphs using Matlab.
•	Implement simple numerical methods for numerical integration. 
•	Troubleshoot with confidence. 


### Description:

<p style="text-align: justify;">There are three main goals of this course redesign: (1) to increase the level of mastery over fundamental programming skills so they can be better utilized/leveraged in future classes as well as their professional careers; (2) to make sure every student is getting the most out of the course, despite its innate bimodal distribution; and (3) to more effectively teach algorithmic thinking. </p>

In the current version of the class, we start by presenting the most basic and fundamental programming concepts, which build upon each other to allow students to solve more complex problems. The material is reinforced through daily homework problems and mini-projects (3 total), as well as plenty of in-class time to work on programming skills. After these fundamental skills are covered, we simply dive into a few applications, such as numerical integration and Euler’s method. In principle, they are simply used to get students exposed to a wider range of applications, but they will be revisited in more depth in the following programming class in the curriculum, Numerical Methods (ME327). 

There is no expectation of prior programming knowledge, so all the content is presented in its most basic form. Nowadays, a significant number of Y1 students come into this class with previous programming experience, which creates a bimodal distribution for this class. On one hand, we have students with significant experience which perceive the class as too elementary and slow-paced. On the other, students with no prior experience require more time to digest and fully understand the fundamental building blocks of programming. These students, in particular, feel like the course is too fast-paced and usually cannot fully comprehend the more advanced skills because they are yet to master the fundamental building blocks of programming. This makes it difficult to ensure all students get the most out of this class, but it is one of the main points that needs to be addressed in this course redesign. 
Another main goal of this work is to introduce more material in algorithmic thinking, which allows students to break down more complex problems, expand their programming capabilities, and apply their skills to more challenging problems. It has been noticed that when students get to more advanced classes, such as Numerical Methods, a significant portion of them have difficulty extending their ME123 knowledge and applying them to slightly different problems. Even though they only need to use their fundamental building blocks, their algorithmic thinking and comfort with such skills is lacking, which in turn causes many difficulties in more advanced courses. 
In order to address these 3 main challenges, a Mastery-based Learning (MBL) approach is proposed. The inspiration behind this approach comes from a KEEN workshop that I attended last summer (Learning from Failure with Mastey-based Learning), which showed me the capabilities of MBL and gave me some great ideas on how to implement it to our curriculum. In general, the MBL approach only allows students to progress through the class once they have demonstrated “mastery” over each key element of the course. This is done by multiple assessments throughout the quarter, with the possibility of retaking each of them until you mastered it. There is no partial credit for these assessments, either the student mastered the skill, or they are still lacking and need to work more on it to continue. For example, the first fundamental skill in the class is “Scripts, Printing, Commenting, and Debugging”. During the first week, all students will be assessed on this skill. If they have demonstrated mastery, they can attempt to demonstrate mastery on the next skill (which builds upon it) during the next assessment period. For the students that weren’t able to pass the first assessment, they will then have the opportunity to reassess. These quizzes will test the same skills, but will be different, thus ensuring students are mastering the content rather than memorizing the previous solutions. Each assessment will consist of a short multiple choice Moodle quiz (for theoretical knowledge checks), as well as a practical coding problem. Both need to be completely correct to demonstrate mastery over that specific skill. 
The figure below shows a sample of what the structure and progression of the skills will look like for the course. All skills in dark blue are considered fundamental and mastery of them, along with at least one project, is the minimum required to pass the class. No matter how many assessments a student has passed, they are still required to attend class and at least be exposed to all of the class content, delivered through daily lectures. The green boxes represent supplemental skills that will be covered in class and will help students in the future, however are not strictly required. I will probably incorporate a hierarchy of these as well, so they can’t be done at any order. Finally, we have the purple boxes, which are labeled as “Self-Directed Learning Projects”. These skills are meant for students that want to explore a specific advanced topic in programming/Matlab, which will not be covered during regular lectures. The plan is to come up with some material that students can read, follow a few examples, then implement the skill on their own. This is meant to cater to the student body that has significant coding experience and incentivize them to learn new and “cool” topics.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MBL_SkillTree.jpg" title="MBL Skill Tree" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Proposed distribution of skills throughout the quarter. The skills in dark blue, inside of the “Units” are the fundamental skills of the course and the bare minimum required to pass the class, with at least one project completed. The skills in green are supplementary skills that would bump up the students’ grades and allow them to apply the fundamental skills in different ways. Lastly, the purple skills are “Self-Directed Learning Projects”, which are targeted for more advanced students to go above and beyond and learn new skills on their own. These are just some examples of such skills. 
</div>

Similar to the current version of the course, each class day is divided into a short presentation of a new topic and some time for the students to work on problems and apply their skill in Matlab. I will still deliver the week’s content to every student, but when they break off to work on their own, each student will be practicing problems related to the skill they are currently on. This ensures that students that already have a strong programming background can work ahead, while giving other students more time to develop the fundamental skills necessary to succeed. The fact that most of the skills in this course build upon each other also helps to reinforce previous knowledge that has been mastered.

One of the outcomes of this method is that it will change what it means to pass this course with a C/D. Currently, a student that earns such a grade, probably receives a lot of partial credit, meaning that they have been exposed to many topics, but do not master many of them. With this change, the goal is to still expose students to all the topics through the lectures but give them more time to work on fundamental skills rather than jumping ahead. Therefore, a student that earns a C/D can be sure that they mastered the fundamental skills of the class, but simply did not have the time to work on more advanced topics. The difference is that, now, they are able to leverage that mastery to more effectively learn more advanced skills in the future.  

---


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>


You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
