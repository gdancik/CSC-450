---
layout: page
title: Assignments 
titleDisplay: Assignments 
permalink: /assignments/
order: 3
exclude_from_nav: false 
---

<style>

.hide {
  display:none
}

table, th, td {
  border: 0px solid black;
  border-collapse: collapse;
  text-align: center;
}

td.left {
    text-align: left;
}

a.hide, tr.hide {
    display: none;
}

.due {
    background-color: yellow
}

</style>

<script>
function removeHideClass() {
  var elements = document.getElementsByTagName("tr");
  for (var i = 0; i < elements.length; i++) {
    elements[i].classList.remove("hide");
  }

  element = document.getElementById('hideprevious');
  element.classList.add('hide'); 
} 

</script>

{% comment %}
<div id = 'hidden' class = 'hide' markdown="1">
{% endcomment %}

* Course setup
    * Sign up for [Piazza](https://piazza.com) using your Eastern e-mail address. You will be getting an e-mail with more information shortly.
    * Sign up for [Perusall](https://perusall.com) using your Eastern e-mail address, and enroll in this course. The course code can be found on the syllabus in the [Course Information]({{ site.baseurl }}/info/) section.


* [Autobiography and Piazza Post ]({{ site.baseurl }}/data/hw/Autobiography.pdf) (Due: Friday, 09/08/2023)
* [Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.docx) (Due: Monday, 09/11/2023)
* [Article Discussion - Cellular automata model for evacuation with obstacles](https://perusall.com) (Due: Monday, 09/11/2023)
{% comment %}
* [Article Discussion - Experimental evidence of massive-scale emotional contagion through social networks](https://perusall.com) (Due: Monday, 02/06/2023)
* Find two articles - see posts on [Piazza](https://piazza.com) (Due: Wednesday, 02/08/2023)
* [Article Critique]({{ site.baseurl }}/data/hw/Evaluation-Perusall.pdf) (Due: Monday, 02/13/2023 by 11:00 AM)
</div>
* [Literature Review]({{ site.baseurl }}/data/hw/LitReview.pdf) (Due: Friday, 02/24/2023 by 11:00 AM; submit through [Blackboard](http://easternct.blackboard.com))
* <span class = 'mue'>[Lab Meeting #1]({{ site.baseurl }}/data/hw/LabMeeting1.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Research Proposal]({{ site.baseurl }}/data/hw/Proposal.pdf) (Due: Sunday, 03/05/2023, by 5:00 PM; submit through [Blackboard](http://easternct.blackboard.com))
* [Github Assignment]({{ site.baseurl }}/data/hw/Github.pdf) (Due: Friday, 03/24/2023 by 11:00 AM)
* [Outline]({{ site.baseurl }}/data/hw/Outline.docx) (Due: <strike>Monday, 03/27/2023</strike><span style = 'color:red'>Wednesday, 03/29/2023</span>, by 11:00 AM; submit a hard copy in class)
* [Reference Assignment]({{ site.baseurl }}/data/hw/ReferenceAssignment.docx) (in-class assignment, 03/29/2023)
* [Write a Résumé]({{ site.baseurl }}/data/hw/ResumeAssignment.pdf) (Due: Friday, 03/31/2023) 
* [Abstract Assignment]({{ site.baseurl }}/data/hw/Abstracts.docx) (in-class assignment) 
* <span>[Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due: Friday, 04/21/2023 by 11:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr style = "margin-bottom:5px; margin-top:-5px; color:red;">
* [Research Presentation]({{ site.baseurl }}/data/hw/ResearchPresentation.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com)) 
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 05/10/23 by 11:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr>
* [Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 11/14/18; submit through [Blackboard](http://easternct.blackboard.com)) 
* [LaTeX assignment]({{ site.baseurl }}/data/hw/latex-assignment.pdf) (in-class assignment, 11/14/18) 
    * [Presentation Schedule]({{ site.baseurl }}/data/hw/FinalPresentationSchedule01.pdf)
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Monday, 12/10/18 by 7:00 PM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr>
* Attend [CREATE](http://www.easternct.edu/create/files/2014/12/FINAL-CREATE-2018-Program.pdf) - You may attend at least one of the CS talks between 9:30 - 10:30 (I will bring a sheet for you to sign) or you may attend the poster session between 12:30 - 1:30, and e-mail me a picture of you in front of one of the posters by 5:00 PM Friday 

* [Find an Article ]({{ site.baseurl }}/data/hw/FindArticles.pdf) (in-class assignment, 9/12/18)

***

{% endcomment %}
<br>

<script>
const pattern = RegExp('Due:.*([0-9]{2}/[0-9]+/[0-9]{4})');
elements = document.getElementsByTagName('li');

for (el of elements) {
        var res = pattern.exec(el.innerText);
        if (res != null && res.length >= 2) {
                if (new Date(res[1]) >= new Date()) {
                        el.className = 'due';
                }
        }
}
</script>

{% comment %}
<center>
<div id = 'clicker'>
<a href = '#' style='font-size:120%' onclick = 'viewAll();'>Click to view all assignments</a>
<script>
function viewAll() {
    document.getElementById('hidden').classList.remove('hide');
    document.getElementById('clicker').classList.add('hide');
    document.getElementsByTagName('ul')[0].style.marginBottom = '0px'
}
</script>
{% endcomment %}
