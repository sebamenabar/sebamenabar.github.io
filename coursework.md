---
layout: page
title: Coursework
description: Courses I've taken
image: 
nav-menu: true
show-tile: true
engineering:
    - Linear Algebra
    - Calculus I, II and III
    - General Chemistry
    - Statics and Dynamics
    - Thermodynamics
    - Optimization
    - Differential Equations
    - Probabilities and Statistics
    - Electricity and Magnetism
undergraduate:
    - Advanced Programming
    - Discrete Mathematics
    - Computer Architecture
    - Databases
    - Software Engineering
    - Theory of Automata and Formal Languages
    - Operating Systems and Networks
    - Data Structures and Algorithms
    - Logic for Computer Science
    - Mobile Robotics
    - Distributed Systems
    - Web Applications and Technologies
data-science:
    - Data Mining
    - Pattern Recognition
    - Information Visualization
    - Artificial Intelligence
    - Recommending Systems
    - Statistical Inference
biological:
    - Cell Biology
    - Fundamentals of Biotechnology
    - Biology of Microorganisms
    - Microbiology and Environmental Biotechnology

---


<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <div class="i-am-centeredow">
                <div class="row">
                    <div class="5u -2u 12u$(small)">
                        <h4>Undergraduate CS</h4>
                        <ul>
                            {% for course in page.undergraduate %}
                                <li>{{ course }}</li>
                            {% endfor %}
                        </ul>
                    </div>
                    <div class="5u 12u$(small)">
                        <h4>Data Science Undergrad</h4>
                        <ul>
                            {% for course in page.data-science %}
                                <li>{{ course }}</li>
                            {% endfor %}
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="4u -2u  12u$(small)">
                    <h5>Engineering Common Plan</h5>
                    <ul class="small">
                        {% for course in page.engineering %}
                            <li><small>{{ course }}</small></li>
                        {% endfor %}
                    </ul>
                </div>
                <div class="4u 12u$(small)">
                    <h5>Biological</h5>
                    <ul>
                        {% for course in page.biological %}
                            <li><small>{{ course }}</small></li>
                        {% endfor %}
                    </ul>
                </div>
            </div>
        </div>
    </section>
</div>