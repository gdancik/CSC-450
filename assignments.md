---
layout: page
title: Assignments 
titleDisplay: Assignments 
permalink: /assignments/
order: 3
exclude_from_nav: false 
---

<style>
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

* Course setup
    * Sign up for [Piazza](https://piazza.com) using your Eastern e-mail address. You will be getting an e-mail with more information shortly.
    * Sign up for [Perusall](https://perusall.com) using your Eastern e-mail address, and enroll in this course. The course code can be found on the syllabus in the [Course Information]({{ site.baseurl }}/info/) section.
* [Autobiography and Piazza Post ]({{ site.baseurl }}/data/hw/Autobiography.pdf) (Due: Wednesday, 09/07/2022)
* [Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.docx) (in-class assignment on 09/07/2022)
* [Article Discussion - Cellular automata model for evacuation with obstacles](https://perusall.com) (Due: Monday, 09/12/2022)
* [Article Discussion - Experimental evidence of massive-scale emotional contagion through social networks](https://perusall.com) (Due: Monday, 09/19/2022)
* [Find two articles](https://piazza.com) (Due: Wednesday, 09/21/2022)
* [Article Critique]({{ site.baseurl }}/data/hw/Evaluation-Perusall.pdf) (Due: Monday, 09/26/2022)
* [Literature Review]({{ site.baseurl }}/data/hw/LitReview.pdf) (Due: Monday, 10/10/2022 by 1:00 PM; submit through [Blackboard](http://easternct.blackboard.com))
* <span>[Lab Meeting #1]({{ site.baseurl }}/data/hw/LabMeeting1.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))</span>
* <span style = 'background-color:yellow'>[Research Proposal]({{ site.baseurl }}/data/hw/Proposal.pdf) (Due: Monday, 10/17/2022, by 1:00 PM; submit through [Blackboard](http://easternct.blackboard.com))</span>
<hr style = "margin-bottom:5px; margin-top:-5px; color:red;">
* [Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))
* [Résumé]({{ site.baseurl }}/data/hw/ResumeAssignment.pdf) (Due date: TBD) 
{% comment %}
* [Github Assignment]({{ site.baseurl }}/data/hw/Github.pdf) (Due: Friday, 10/29/20 by 1:00 PM)
* [Outline]({{ site.baseurl }}/data/hw/Outline.docx) (Due: Monday, 11/02/21, by 1:00 PM; submit a hard copy in class)
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Friday, 11/19/2022 by 1:00 PM) 
* [Research Presentation]({{ site.baseurl }}/data/hw/ResearchPresentation.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com)) 
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 12/08/20 by 2:00 PM; submit through [Blackboard](http://easternct.blackboard.com)) 
* [Reference Assignment]({{ site.baseurl }}/data/hw/ReferenceAssignment.docx) (in-class assignment, 10/26/20)
* [Abstract Assignment]({{ site.baseurl }}/data/hw/Abstracts.docx) (in-class assignment, 11/02/20) 
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

