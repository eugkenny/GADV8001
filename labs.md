---
layout: page
title: Labs
permalink: /labs/
---

Materials for offline practical labs using the [Bullet Physics Engine](https://pybullet.org/wordpress/) and OpenGL.
Source code to accompany these labs is available [here]({{ site.baseurl }}/labs/Code.zip). 
There is likely to be a missing .dll file that will prevent compilation initially - a quick search online should rectify this. 
I will post a link here once someone notifies me of the details.

It is important that you attempt at least one lab every week (feel free to move ahead if you have the time) and ensure that you take the time to experiment with the code - attempt to break things, play with parameters to see the effects. You should also use the online Bullet [documentation](https://pybullet.org/wordpress/index.php/forum-2/) to extend your lab work and see what else is possible.


Ultimately, the labs will lead to your major assignmemnt for the semester.

<ul id="archive">
{% for labs in site.data.labs %}
      <li class="archiveposturl">
        <span><a href="{{ site.baseurl }}/{{ labs.dirname }}/{{ labs.filename }}.pdf">{{ labs.title }}</a></span><br>
<span class = "postlower">
<!-- <strong>tl;dr:</strong> -->{{ labs.tldr }}</span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right; padding-right: .5em">
<!--
	<a href="https://github.com/{{ site.githubdir}}/tree/master/{{ lectures.dirname }}"><i class="fab fa-github"></i></a>&nbsp;&nbsp;
	<a href="https://github.com/{{ site.githubdir}}/tree/master/{{ lectures.dirname }}/{{ lectures.filename}}.Rmd"><i class="fab fa-r-project"></i></a>&nbsp;&nbsp;
	<a href="https://github.com/{{ site.githubdir}}/blob/master/{{ lectures.dirname }}/{{ lectures.filename}}.pdf"><i class="fas fa-file-pdf"></i></a>
-->
</strong> 
      </li>
{% endfor %}
</ul>
