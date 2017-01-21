---
layout: page
title: R&eacute;sum&eacute;
permalink: /resume/
---

<a href="../assets/Jeremy-Hintz-Resume.pdf" target="_blank" class="myButton">Download PDF</a>
<article class="post">
	<h1 id="myName"><strong>JEREMY </strong><span style="font-weight: 400;">HINTZ</span></h1>
	<p>jeremy.hintz@gmail.com // 214.883.1547</p>
	<hr>
	<h2 id="resumeSubhead"><strong>PROFESSIONAL EXPERIENCE</strong></h2>
	{% for employer in site.data.resume.employers %}
	    <div>
	        <img src="{{ employer.logo | prepend: site.baseurl }}" alt="{{ employer.name }}" id="employerLogo">
	        <h6 align="right">{{ employer.timerange }}</h6>
	    </div>
	    <h3>{{ employer.title }}</h3>
	    <ul>
	    {% for bullet in employer.bullets %}
		    <li id="resumeBullet">
		        {{ bullet }}
		    </li>
	    {% endfor %}
	    </ul>
	{% endfor %}
	<hr>
	<h2 id="resumeSubhead"><strong>EDUCATION</strong></h2>
	{% for school in site.data.resume.education %}
		<div>
			{% if school.logo %}
		        <img src="{{ school.logo | prepend: site.baseurl }}" alt="{{ school.name }}" id="utLogo">
		    {% endif %}
	    </div>
	{% endfor %}
    <!-- M.S. -->
    <h3 id="resumeEntry"><strong>M.S.</strong> Computer Sciene, Engineering, and Math</h3>
    <h6>Aug 2015 - Dec 2016</h6>
    <p id="resumeDescription"><strong>Thesis:</strong> <a href='#'>Deep Generative Adversarial Networks</a>
    <br><strong>Appointments:</strong> Teaching Assistant, CS 380L: Advanced Operating Systems (1 semester)</p>
    <!-- B.S. -->
    <h3 id="resumeEntry"><strong>B.S.</strong> Computer Sciene</h3>
    <h6>Aug 2011 - May 2015</h6>
    <p><strong>Appointments:</strong> Teaching Assistant, CS 439: Operating Systems (4 semesters),
    <br>Director of Web Development, The Daily Texan (2 semesters)</p>
    <hr>
	<h2 id="resumeSubhead"><strong>HONORS AND CERTIFICATIONS</strong></h2>
	<h3 id="resumeEntry">Mensa International Member</h3>
	<h3 id="resumeEntry">Duane Lee Moody Scholar</h3>
	<p>Awarded to outstanding engineering student</p>
	<h3 id="resumeEntry">Browning Endowed Scholar</h3>
	<p>Awarded to student displaying academic excellence</p>

</article>


