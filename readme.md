# Introduction
we are going to finish 7 tasks and each of us are only allow to finish one task at most.
They are:

Task 1: Starting issues
- Create new issues for each task and label each of them.

Task 2: Project board 
- Name the project broad and marks some actions as done when the task is fulfiled.

Task 3: Set up readme.md (NOW haha)
- Edit the readme file to show what to finish for each task.

Task 4: Write C code
- Set up a Github Action to run a simple C program that created by yourself (can be justsimple as Hello World). 

Task 5: Get a status badge
- Edit the Code part of this readme and get a workflow status badge for the code created in task 4.

Task 6: Showcase your team 
- Edit readme but also show the information required in the task.  

Task 7: Register your repo
- Edit the readme to add a link of our team, and request for review from @chuckjee.
# Code
```c
{% include_relative code.c %}
```
![workflow status badge](https://github.com/csci3251-2023/project-team-g/actions/workflows/c-cpp.yml/badge.svg)
# Contributors
<ul>
{% for stu in site.stu %} 
    <li>
        <p>
         <img src="{{stu.image}}" alt="icon" width="50" height="50"> @{{ stu.user }}  ({{ stu.name }})
        </p>
      <ul><li><p>{{ stu.content | markdownify }}</p></li></ul>
  </li>
{% endfor %}
</ul>
=======
# Last updated 
{{ site.time }}

 
