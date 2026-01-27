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
* Using the links on Blackboard, log on to [Piazza](https://piazza.com) and complete the poll (Due: 08/30/2025)
{% endcomment %}

* [Autobiography and Piazza Post ]({{ site.baseurl }}/data/hw/Autobiography.pdf) (Due: Thursday, 01/29/2026)
* [Article Discussion - Cellular automata model for evacuation with obstacles](http://easternct.blackboard.com) (use Perusall link on Blackboard) (Due: Tuesday, 02/03/2026)
{% comment %}
* <span class = 'ddue'>[Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.docx) (submit through [Blackboard](http://easternct.blackboard.com) unless you were checked off in class) </span>
* [Article Discussion - Experimental evidence of massive-scale emotional contagion through social networks](https://easternct.blackboard.com) (use Perusall link on Blackboard) (Due: Tuesday, 09/16/2025)
* [Article Critique]({{ site.baseurl }}/data/hw/Evaluation-Perusall.pdf) (Due: <strike>Tuesday</strike>Thursday, 09/25/2025 by 9:30 AM)
* <span class = 'ddue'>[Lab Meeting #1]({{ site.baseurl }}/data/hw/LabMeeting1.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Literature Review]({{ site.baseurl }}/data/hw/LitReview.pdf) (Due: Monday, 10/06/2025 by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com))
* [Research Proposal]({{ site.baseurl }}/data/hw/Proposal.pdf) (Due: Monday, 10/13/2025, by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com))
* <span class = "xdue">[Github Assignment]({{ site.baseurl }}/data/hw/Github.pdf) (Due: 11/03/2025; submit through [Blackboard](http://easternct.blackboard.com))
* [Outline]({{ site.baseurl }}/data/hw/Outline.docx) (Due: Tuesday, 11/04/2025, by 9:30 AM; submit through [Blackboard](http://easternct.blackboard.com))
* <span class = 'xdue'>[Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due: Monday, 11/17/2025 by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr style = "margin-bottom:5px; margin-top:-10px; color:maroon;">
* [Résumé]({{ site.baseurl }}/data/hw/Resume.pdf) (Due: Tuesday, 12/02/2025 by noon) 
<hr style = "margin-bottom:5px; margin-top:-10px; color:maroon;">
* [Poster Presentation]({{ site.baseurl }}/data/hw/ResearchPresentationPoster.pdf) (Due: Friday, 12/05/2025 by 3:00 PM through [Blackboard](http://easternct.blackboard.com) and the [Copy Center](https://www.easternct.edu/communications-marketing/services/copy-center.html); see assignment for details)
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due: Tuesday, 12/09/2025 by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 

* Find an article - see post on [Piazza](https://piazza.com) (Due: Monday, 09/16/2025)
* [Reference Assignment]({{ site.baseurl }}/data/hw/ReferenceAssignment.docx) (in-class assignment, 03/19/2025)
* <span class = 'ddue'>[Abstract Assignment]({{ site.baseurl }}/data/hw/Abstracts.docx) (in-class assignment)</span> 
* <span class = "due">[Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
</div>
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 05/10/23 by 11:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr>
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 11/14/18; submit through [Blackboard](http://easternct.blackboard.com)) 
* [LaTeX assignment]({{ site.baseurl }}/data/hw/latex-assignment.pdf) (in-class assignment, 11/14/18) 
    * [Presentation Schedule]({{ site.baseurl }}/data/hw/FinalPresentationSchedule01.pdf)
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Monday, 12/10/18 by 7:00 PM; submit through [Blackboard](http://easternct.blackboard.com)) 
<hr>
* Attend [CREATE](http://www.easternct.edu/create/files/2014/12/FINAL-CREATE-2018-Program.pdf) - You may attend at least one of the CS talks between 9:30 - 10:30 (I will bring a sheet for you to sign) or you may attend the poster session between 12:30 - 1:30, and e-mail me a picture of you in front of one of the posters by 5:00 PM Friday 

* [Find an Article ]({{ site.baseurl }}/data/hw/FindArticles.pdf) (in-class assignment, 9/12/18)

***
* [Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.docx) (Due: Friday, 09/06/2025) 

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
