---
layout: default
permalink: /teaching/
title: Teaching
nav: true
nav_order: 6
---
{% assign teaching_name_size = site.teaching_name | size %}
{% assign teaching_description_size = site.teaching_description | size %}

{% if teaching_name_sizee > 0 or teaching_description_size > 0 %}

  <div class="header-bar">
    <h1>{{ site.teaching_name}}</h1>
    <h4>{{ site.teaching_description }}</h4>
  </div>
  {% endif %}

<div class="content">
    <h3 class="mt-4 font-weight-bold">University of Toronto</h3>
    <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Introduction to Computer Programming</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC108
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Fall 2021, Fall 2023: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, first-year introduction to programming in python taught by <a href="https://www.michaelliut.ca/">Michael Liut</a> and <a href="https://www.utm.utoronto.ca/math-cs-stats/people/rutwa-engineer">Rutwa Engineer</a>.</li>
            </ul>
        </div>
    </div>
    <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Introduction to Computer Science</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC148
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Winter 2021, Winter 2022: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, first-year introduction to computer science and basic data structures taught by <a href="https://www.michaelliut.ca/">Michael Liut</a> and <a href="https://www.cs.toronto.edu/~bogdan/">Bogdan Simion</a>.</li>
                <li class="list-group-item">— Week 1: <a class="btn-learning" href="/assets/pdf/csc148/1.1.pdf">1.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/1.2.pdf">1.2 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/1.3.pdf">1.3 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/1.4.pdf">1.4 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/1.5.pdf">1.5 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/1.6.pdf">1.6 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 2: <a class="btn-learning" href="/assets/pdf/csc148/2.1.pdf">2.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/2.2.pdf">2.2 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/2.3.pdf">2.3 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 3: <a class="btn-learning" href="/assets/pdf/csc148/2.4.pdf">2.4 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/2.5.pdf">2.5 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/2.6.pdf">2.6 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/2.7.pdf">2.7 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 4: <a class="btn-learning" href="/assets/pdf/csc148/3.1.pdf">3.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/3.2.pdf">3.2 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/3.3.pdf">3.3 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/3.4.pdf">1.4 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 5: <a class="btn-learning" href="/assets/pdf/csc148/4.1.pdf">4.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/4.2.pdf">4.2 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/4.3.pdf">4.3 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/4.4.pdf">4.4 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 6: <a class="btn-learning" href="/assets/pdf/csc148/5.1.pdf">5.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/5.2.pdf">5.2 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 7: <a class="btn-learning" href="/assets/pdf/csc148/6.1.pdf">6.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/6.2.pdf">6.2 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/6.3.pdf">6.3 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 8: <a class="btn-learning" href="/assets/pdf/csc148/6.4.pdf">6.4 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/6.5.pdf">6.5 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/6.6.pdf">6.6 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/6.7.pdf">6.7 <i class="fa fa-external-link small-icon"></i></a>
                </li>
                <li class="list-group-item">— Week 9: <a class="btn-learning" href="/assets/pdf/csc148/6.8.pdf">6.8 <i class="fa fa-external-link small-icon"></i> </a>
                </li>
                <li class="list-group-item">— Week 10: <a class="btn-learning" href="/assets/pdf/csc148/7.1.pdf">7.1 <i class="fa fa-external-link small-icon"></i></a> | <a class="btn-learning" href="/assets/pdf/csc148/7.2.pdf">7.2 <i class="fa fa-external-link small-icon"></i></a>
                </li>
            </ul>
        </div>
    </div>
    <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Introduction to the Theory of Computation</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC236
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Fall 2022: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, second-year course covering mathematical induction, correctness proofs for algorithms, recurrence equations (including the Master Theorem), and an introduction to automata and formal languages, taught by <a href="https://www.michaelliut.ca/">Michael Liut</a>.</li>
                <li class="list-group-item">— Intro to LaTEX Tutorial: <a class="btn-learning" href="/assets/pdf/csc236/latexintro.pdf">slides <i class="fa fa-external-link small-icon"></i> </a></li>
                <li class="list-group-item">— Simple Induction Tutorial: <a class="btn-learning" href="/assets/pdf/csc236/induction.pdf">slides <i class="fa fa-external-link small-icon"></i> </a></li>
                <li class="list-group-item">— Runtime Analysis Tutorial: <a class="btn-learning" href="/assets/pdf/csc236/runtime.pdf">slides <i class="fa fa-external-link small-icon"></i> </a></li>
            </ul>
        </div>
    </div>
    <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Computer Organization</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC258
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Winter 2022: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, second-year course covering fundamental concepts in computer architecture and organization, including machine languages, instruction execution, memory systems, and digital logic, with practical practicals in assembly, taught by <a href="https://utmandrew.bitbucket.io/">Andrew Petersen</a>.</li>
                <li class="list-group-item">— Ripes Intro Tutorial: <a class="btn-learning" href="/assets/pdf/csc258/ripes_intro.pdf">Slides <i class="fa fa-external-link small-icon"></i> </a></li>
                <li class="list-group-item">— Control Flow Tutorial: <a class="btn-learning" href="/assets/pdf/csc258/control_flow.pdf">Slides <i class="fa fa-external-link small-icon"></i> </a></li>
                <li class="list-group-item">— Arrays & Functions Tutorial: <a class="btn-learning" href="/assets/pdf/csc258/arrays.pdf">Slides <i class="fa fa-external-link small-icon"></i></a></li>
            </ul>
        </div>
    </div>
    <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Current Approaches to Ethics for Computer Scientists</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC398
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Fall 2023: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, third-year course covering ethics in various branches of computer science (industry, research, society) taught by <a href="https://mikepawliuk.ca/">Micheal Pawliuk</a>.</li>
            </ul>
        </div>
    </div>
     <div class="card mt-3">
        <div class="p-3">
            <div class="row">
                <div class="col-sm-10">
                    <h5 class="font-weight-bold">Introduction to Databases</h5>
                </div>
                <div class="col-sm-2 text-left text-sm-right">
                    <span class="course-badge">
                        CSC343
                    </span>
                </div>
            </div>
            <h6 class="font-italic mt-2 mt-sm-0">Winter 2023: Teaching Assistant</h6>
            <ul class="card-text font-weight-light list-group list-group-flush">
                <li class="list-group-item">Undergraduate-level, third-year course introducing database management systems, covering relational data models, SQL, database design, integrity constraints, and key concepts in query processing and transaction management, taught by <a href="https://www.michaelliut.ca/">Michael Liut</a>.</li>
            </ul>
        </div>
    </div>
    <!-- Add more courses as needed -->
</div>