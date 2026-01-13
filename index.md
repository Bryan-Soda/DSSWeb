---
---


{% include section.html size="hero" %}

{%comment%} ^^This section had to placed prior to the #HERO for the 'datasize' to be applied (ie: allows this section to have hero aspects applied)   {%endcomment%}
# data science society @ ucm
<hr>
<p style="text-align: center;">Welcome to the Data Science Society at UC Merced! We are a student-led organization dedicated to learning, building, and exploring data science together. Browse our events, workshops, projects, and see how YOU can get involved.</p>
<!-- buttons -->
{%
  include button.html
  text="Join Us!"
  style="large"
  link="https://linktr.ee/dssucm"
%}
{%
  include button.html
  text="Events"
  style="large"
  link="./events"
%}
<!--  -->
{% include section.html 
background="images/blue.png" 
size="mission"
repeat="repeat"  %}


# **Mission Statement**
<hr>
<p style="text-align: center;">Our mission is to <u><b>cultivate a community</b></u> of innovators passionate about data-driven discovery. <u><b>Empower students</b></u> to master the tools of data science, apply them to real-world problems, and collaborate across disciplines to <u><b>generate insight, impact, and innovation.</b></u></p>

{% include card.html
  image="images/photo.jpg"
  style="pillars"
  title="Community"
  description="We are building a community of curious minds ready to challenge themselves and explore the unknown. Whether you’re a beginner or a pro, if you want to build the future, you belong here."
%}

{% include card.html 
  style="pillars"
  image="images/photo.jpg"
  title="Education"
  description="From Python to data Visualization, we turn classroom theory into real-world practice. Our hands-on workshops and collaborative projects are built to take you beyond the basics."
%}

{% include card.html 
  image="images/photo.jpg"
  style="pillars"
  title="Impact"
  description="The future of data science is rooted in its ability to solve problems that matter. From local challenges to global trends, we are gathering the curious minds needed to turn data into a tool for innovation."
%}



