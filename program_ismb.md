---
layout: page
title: Program BioVis@ISMB
permalink: /program_ismb/
back_title: ISMB
back_url: ismb
---


## BioVis@ISMB 2018 Program (Preliminary)

### July 9, 2018

### Program

The symposium will be a one-day single-track event at ISMB. The event will feature keynote and invited talks, paper sessions, highlight talks, workshops, and posters. 
<br>
<br>

<!--
A full list of accepted papers is available [here]({{site.baseurl}}/papers_ismb_accepted/).
<br>
-->

<!-- WELCOME --->
<div>
    <div class="sumTime2">10:15 - 10:20</div>
    <div>
        <div class="sumContent">BioVis Welcome</div>
          <div class="sumDetail" style="padding-left:120px;"><i>Marc Streit</i></div>
    </div>
</div>

<hr class="style-one">


<!-- SESSION 1 --->

<div>
    <div class="sumTime2"> 10:20 - 12:40</div>
    <div>
        <div class="sumContent">1st Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Marc Streit</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session1"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><a href="{{paper.doi}}"> [{{paper.type}}] </a></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- SESSION 2 -->
<hr class="style-one">

<div>
    <div class="sumTime2">2:00 - 4:00</div>
    <div>
        <div class="sumContent">2nd Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: G. Elisabeta Marai</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session2"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><a href="{{paper.doi}}"> [{{paper.type}}] </a></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- SESSION 3 -->
<hr class="style-one">

<div>
    <div class="sumTime2">4:40 - 5:50</div>
    <div>
        <div class="sumContent">3rd Session</div>
    </div>
    <div class="sumDetail" style="padding-left:120px;"><i>Session Chair: Kay Nieselt</i> </div>
    <div class="sumDetail" style="padding-left:120px;font-size:12px;"><i>(* indicates presenting author)</i> </div>	
</div>

{% for paper in site.data.program2018%}
{% if paper.session == "session3"%}
  <div>
      <div class="sumTime" style="padding-top:5px;"> {{paper.start}} - {{paper.end}}</div>
      {% if paper.doi != nil %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;">
          <b><a href="{{paper.doi}}"> [{{paper.type}}] </a></b> <b>{{paper.title}}</b></div>
      </div>
      {% else %}
      <div>
          <div class="ttile" style="padding-left:120px; padding-top:5px;"> <b>[{{paper.type}}] {{paper.title}}</b></div>
      </div>
      {% endif %}
      <div class="sumDetail" style="padding-left:120px;"> <em>Authors:</em> {{paper.authors}}</div>
  </div>
{% endif %}
{% endfor %}

<!-- CLOSING REMARKS AND POSTER SESSION -->
<hr class="style-one">
<div>
    <div class="sumTime2">5:50 - 6:00</div>
    <div>
        <div class="sumContent">Closing Remarks</div>
          <div class="sumDetail" style="padding-left:120px;"><i>Kay Nieselt</i></div>
    </div>
</div>

<hr class="style-one">


<div>
    <div class="sumTime2">6:00 - 7:00</div>
    <div>
        <div class="sumContent">Poster Session</div>
       
		<div class="sumDetail" style="padding-left:120px;"><a href="https://www.iscb.org/cms_addon/conferences/ismbeccb2017/posterlist.php?cat=D?">BioVis posters</a></div>
		
    </div>
</div>



## Invited Speakers


<h3> Keynote Speaker</h3>
<a name="martin"></a>
<div class="talk">
    <div class="ttitle">0ne successful data exploration—many explanations
        <!--{% if talk.slides %}
        <span class="tspeaker" style="float: right;"><a href="{{ site.baseurl }}/files/{{talk.slides}}">Download
            Slides</a></span>
        {% endif %}-->
    </div>
    <div><span class="tspeaker"><a href="http://mkweb.bcgsc.ca/">Martin Krzywinski</a></span>, <span> Michael Smith Genome Science Centre </span></div>

    <div class="tportrait"><img src="{{ site.baseurl}}/images/speakers/martin_krzywinski-2.jpg" style="width: 250px;" alt="E.Franzosa">
    </div>

    <div class="tbioabstract">

        <div class="tabstract"><b>Abstract:</b>
        Without good practices in data exploration, we cannot have answers. Without good design practices, we cannot have good explanations of these answers. This is confounded by the fact that most answers are neither self-explanatory nor immediately obviously correct and as such their reception and impact is directly related to the quality of the explanation.

By now, most of us are familiar with the guidelines for visualization and the many human perception studies that can help us make good choices in encodings, colors, and type. The principles that underpin these choices are now generally well accepted and implemented in many applications. But although it is now easy to make a pile of plots, it is generally very challenging to determine how to sort through the pile to select and order a set for an engaging and expository data presentation.  

The process of design, which is a kind of choreography for the page, can be of great help in assembling individual data visualizations into a cohesive explanation across many levels of detail. In the same way that visualizations are a way to organize data, design is a way to organize visualizations. 

I will share with you my experiences in combining science, visualization and design to create explanations, promote engagement, inspire imagination and, where possible, provide visual support in the often vexing process of research. 
        </div>

        <div class="tbio"><b>Bio:</b>
        Martin Krzywinski is known for his work in bioinformatics, data visualization and the interface of science and art. He applies design, both data and artistic, to assist discovery, explanation and engagement with scientific data and concepts. His information graphics have appeared in the New York Times, Wired, Scientific American and covers of numerous books and scientific journals such as Nature and Genome Research. 
        </div>
    </div>
</div>
