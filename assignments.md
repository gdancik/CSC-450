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

<table style = 'width:100%'>
<tr style = 'border-bottom: 1px solid black'>
<th style = 'width:52%'><br>Assignment </th>
<th style = 'width:24%'>CSC 450-01<br>(MW 4:00 - 5:15) </th>
<th style = 'width:24%'>CSC 450-02<br>(MWF 1:00 - 1:50) </th>
</tr>

{% include hwRow.html
hide = "hide"
due1 = "Due: Monday, 9/9/19" 
due2 = "Due: Friday, 9/6/19" 
name = "Autobiography and Piazza Post"
link = "data/hw/Autobiography.pdf"
%}

{% include hwRow.html 
hide = "hide"
due1 = "Due: Wednesday, 9/11/19" 
due2 = "Due: Friday, 9/6/19" 
name = "CA Evauation Article" link = "data/hw/Varas_CA_model_evacuation.pdf" 
text = "To prepare for in-class discussion, read the article and answer the questions on [Blackboard](http://easternct.blackboard.com) under the \'Assignments\' link.
"%}

{% include hwRow.html
hide = "hide"
name = "CA Evacuation Article Discussion" 
link = "/data/hw/Evaluation-CA-Evacuation.docx"
due1 = "in-class assignment"
due2 = "in-class assignment"
%}


{% include hwRow.html 
hide = "hide"
due1 = "in-class assignment" 
due2 = "in-class assignment" 
name = "Searching the Literature" link = "data/hw/LitSearch.pdf" 
%}


{% include hwRow.html 
hide = "hide"
due1 = "Due: Wednesday, 9/18/19"
due2 = "Due: Friday, 9/13/19" 
name =  "FB Article"
link = "/data/hw/FB.pdf"
due1 = "Due: Wednesday, 9/18/19"
text = "- To prepare for in-class discussion, read the article and answer the questions on [Blackboard](http://easternct.blackboard.com) under the 'Assignments' link"
%}


{% include hwRow.html
hide = "hide"
name = "FB Article Discussion" 
link = "/data/hw/Evaluation-FB.docx"
due2 = "in-class assignment"
due1 = "in-class assignment"
%}

{% include hwRow.html 
hide = "hide"
due1 = "(Wednesday, 9/18/19)"
due2 = "Due: Monday, 9/16/19"
text = "[Piazza assignment](http://piazza.com)"
%}

{% include hwRow.html
hide = "hide"
name = "Article Evaluation" 
link = "/data/hw/Evaluation.docx"
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
due1 = "Wednesday, 9/25/19"
due2 = "Friday, 9/20/2019"
%}

{% include hwRow.html 
hide = "hide"
due1 = "Due: Friday, 9/27/19 by 5:00 PM"
due2 = "Due: Friday, 9/27/19 by 5:00 PM"
name = "Literature Review" link = "data/hw/LitReview.pdf" 
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
%}


{% include hwRow.html 
hide = "shide"
name = "Lab Meeting #1" link = "data/hw/LabMeeting1.pdf" 
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
due2 = "Due dates will vary"
due1 = "Due dates will vary"
%}

{% include hwRow.html 
hide = "shide"
name = "Research Proposal" link = "data/hw/Proposal.pdf" 
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
due2 = "Friday, 10/4/2019 by 5:00 PM"
due1 = "Friday, 10/4/2019 by 5:00 PM"
%}


{% include hwRow.html 
hide = "shide"
name = "Github Assignment" link = "data/hw/Github.pdf"
class1 = "due"
class2 = "due" 
due2 = "Wednesday, 10/23/2019 by 4:00 PM"
due1 = "Wednesday, 10/23/2019 by 1:00 PM"
%}

{% include hwRow.html
hide = "shide"
name = "Reference Assignment" 
link = "/data/hw/ReferenceAssignment.docx"
due2 = "in-class assignment"
due1 = "in-class assignment"
%}

<tr> <td colspan = "3"> <hr></td>
</tr>

{% include hwRow.html 
hide = "shide"
name = "Research Outline" link = "data/hw/Outline.docx"
class1 = "due"
class2 = "due" 
due1 = "Friday, 11/01/2019 by 5:00 PM"
due2 = "Friday, 11/01/2019 by 5:00 PM"
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
%}



{% include hwRow.html 
hide = "shide"
name = "Lab Meeting #2" link = "data/hw/LabMeeting2.pdf" 
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
class1 = "due"
class2 = "due"
due2 = "Due dates will vary"
due1 = "Due dates will vary"
%}

{% include hwRow.html 
hide = "shide"
name = "Rough Draft" link = "data/hw/ResearchPaper.pdf" 
text = "(Submit through [Blackboard](http://easternct.blackboard.com))"
class1 = "due"
class2 = "due"
due2 = "11/15/2019"
due1 = "11/15/2019"
%}


<tr> <td colspan = "3">
<br><br>
<a id = 'hideprevious' href = '#' onclick = 'removeHideClass();'>View all previous assignments </a>
</td></tr>

</table>

{% comment %}
* [Searching the Literature]({{ site.baseurl }}/data/hw/LitSearch.pdf) (in-class assignment on 9/05/18)
    * [Article Discussion]({{ site.baseurl }}/data/hw/Evaluation-CA-Evacuation.docx)
* [Find an Article ]({{ site.baseurl }}/data/hw/FindArticles.pdf) (in-class assignment, 9/12/18)
* [FB Article]({{ site.baseurl }}/data/hw/FB.pdf) - To prepare for in-class discussion, read the article and answer the questions on [Blackboard](http://easternct.blackboard.com) under the 'Assignments' link (Due: Wednesday, 9/19/18)
    * [Article Discussion]({{ site.baseurl }}/data/hw/Evaluation-FB.docx)
* [Article Critique]({{ site.baseurl }}/data/hw/Evaluation.docx) (Due: Friday, 9/21/18 by 4:00 PM)
* [Literature Review]({{ site.baseurl }}/data/hw/LitReview.pdf) (Due: Friday, 9/28/18, at 4:00 PM; submit through [Blackboard](http://easternct.blackboard.com))
* [Lab Meeting #1]({{ site.baseurl }}/data/hw/LabMeeting1.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))
* [Research Proposal]({{ site.baseurl }}/data/hw/Proposal.pdf) (Due: Friday, 10/05/18, at 4:00 PM; submit through [Blackboard](http://easternct.blackboard.com))
* [Reference Assignment]({{ site.baseurl }}/data/hw/ReferenceAssignment.docx) (in-class assignment, 10/22/18)
* [Abstract Assignment]({{ site.baseurl }}/data/hw/Abstracts.docx) (in-class assignment, 10/31/18) 
* [Lab Meeting #2]({{ site.baseurl }}/data/hw/LabMeeting2.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com))
* [Rough Draft]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Wednesday, 11/14/18; submit through [Blackboard](http://easternct.blackboard.com)) 
* [LaTeX assignment]({{ site.baseurl }}/data/hw/latex-assignment.pdf) (in-class assignment, 11/14/18) 
<hr>
* [Research Presentation]({{ site.baseurl }}/data/hw/ResearchPresentation.pdf) (Due dates will vary; submit through [Blackboard](http://easternct.blackboard.com)) 
    * [Presentation Schedule]({{ site.baseurl }}/data/hw/FinalPresentationSchedule01.pdf)
* [Final Paper]({{ site.baseurl }}/data/hw/ResearchPaper.pdf) (Due date: Monday, 12/10/18 by 7:00 PM; submit through [Blackboard](http://easternct.blackboard.com)) 
* [Résumé]({{ site.baseurl }}/data/hw/Resume.pdf) (Due date: Wednesday, 4/04/18) 
<hr>
* Attend [CREATE](http://www.easternct.edu/create/files/2014/12/FINAL-CREATE-2018-Program.pdf) - You may attend at least one of the CS talks between 9:30 - 10:30 (I will bring a sheet for you to sign) or you may attend the poster session between 12:30 - 1:30, and e-mail me a picture of you in front of one of the posters by 5:00 PM Friday 

***
{% endcomment %}
