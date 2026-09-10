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


* <span class = 'dude'>[Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.docx) (in-class assignment, 09/01/2026) </span>
* [Autobiography and Piazza Post ]({{ site.baseurl }}/data/hw/Autobiography.pdf) (Due: Thursday, 09/03/2026)
* [Article Discussion - Cellular automata model for evacuation with obstacles](http://easternct.blackboard.com) (use Perusall link on Blackboard) (Due: Thursday, 09/10/2026)
<hr style = "margin-bottom:5px; margin-top:-10px; color:maroon;">
* [Article Discussion - Experimental evidence of massive-scale emotional contagion through social networks](https://easternct.blackboard.com) (use Perusall link on Blackboard) (Due: Tuesday, 09/17/2026)
* [Literature Review]({{ site.baseurl }}/data/hw/LitReview.pdf) (Due: Monday, 10/05/2026; submit through [Blackboard](http://easternct.blackboard.com))
{% comment %}
* [Article Critique]({{ site.baseurl }}/data/hw/Evaluation-Perusall.pdf) (Due: Tuesday, 02/17/2026 by 9:30 AM)
* <span class = 'ddue'>[Lab Meeting #1]({{ site.baseurl }}/data/hw/LabMeeting1.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Research Proposal]({{ site.baseurl }}/data/hw/Proposal.pdf) (Due: Thursday, 03/05/2026, by 9:30 AM; submit through [Blackboard](http://easternct.blackboard.com))
* <span class = "dxue">[Github Assignment]({{ site.baseurl }}/data/hw/Github.pdf) (Due: 03/31/2026; submit through [Blackboard](http://easternct.blackboard.com))
* [Outline]({{ site.baseurl }}/data/hw/Outline.docx) (Due: Tuesday, 04/02/2026, by 9:30 AM; submit through [Blackboard](http://easternct.blackboard.com))
* <span class = 'dxue'>[Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due: Monday, 04/20/2026 by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
* [Poster Presentation]({{ site.baseurl }}/data/hw/ResearchPresentationPoster.pdf) (Due: Friday, 05/08/2026 by 3:00 PM through [Blackboard](http://easternct.blackboard.com) and the [Copy Center](https://www.easternct.edu/communications-marketing/services/copy-center.html); see assignment for details)
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due: Tuesday, 05/12/2026 by 8:00 AM; submit through [Blackboard](http://easternct.blackboard.com)) 
{% endcomment %}


{% comment %}
* [Résumé]({{ site.baseurl }}/data/hw/Resume.pdf) (Due: Tuesday, 12/02/2025 by noon) 
<hr style = "margin-bottom:5px; margin-top:-10px; color:maroon;">

* Find an article - see post on [Piazza](https://piazza.com) (Due: Monday, 09/16/2025)
* [Reference Assignment]({{ site.baseurl }}/data/hw/ReferenceAssignment.docx) (in-class assignment, 03/19/2025)
* <span class = 'ddue'>[Abstract Assignment]({{ site.baseurl }}/data/hw/Abstracts.docx) (in-class assignment)</span> 
* <span class = "due">[Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
</div>
<hr>
* Attend [CREATE](http://www.easternct.edu/create/files/2014/12/FINAL-CREATE-2018-Program.pdf) - You may attend at least one of the CS talks between 9:30 - 10:30 (I will bring a sheet for you to sign) or you may attend the poster session between 12:30 - 1:30, and e-mail me a picture of you in front of one of the posters by 5:00 PM Friday 


{% comment %}
<div id = 'hidden' class = 'hide' markdown="1">
* Using the links on Blackboard, log on to [Piazza](https://piazza.com) and complete the poll (Due: 08/30/2025)
{% endcomment %}

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
