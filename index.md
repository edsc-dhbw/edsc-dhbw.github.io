# Enterprise Data Science Center - DHBW Mannheim

The Enterprise Data Science Center (EDSC) at [DHBW Mannheim](http://www.dhbw-mannheim.de) was established to offer services for and to contribute to the evolution of data science. Based on technologies like Cloud Computing and Internet-of-Things (IoT), the extraction of knowlegde from BigData sources - within an enterprise or external - will be the base for future success of an enterprise in the era of digitalisation. Industry 4.0 can be seen as an approach to combine the technologies in a future adaptive IT world. With the focus to support a better human-controlled real-time decision making process by providing knowledge from data analysis of diverse data sources and thousands of sensor running on a managed scalable and fault-tolerant infrastructure, the EDSC will significantly contribute to the development of reliable components for the future enterprise IT.  

Services will be offered for all members of the DHBW for 
* education and lecture purposes
* for professional development courses 
* research projects
within the the [DHBW](http://www.dhbw.de) university 

The [EDSC](http://www.edsc.dhbw-mannheim.de) contributes to the following research areas:

* Adaptive Cloud Computing
* (Industrial) Internet of Things
* Big Data and complex event processing
* Data Science and Analytics on Big Data
* Industry 4.0
* IT Security in connected systems

## Services
The DHBW Cloud Computing Competence Center (4C) as a part of the EDSC provides services for the education and research within DHBW. The services will be provided on a best effort approach and without any Quality-of-Service definition.

EDSC-4C offers (and plans to offer) Cloud services on the following level: 

* Infrastructure as a Service (IaaS)
* Software as a Service (SaaS)
* Data as a Service (DataaaS) 
* eLaaS (eLearning as a Service) 

## Getting Started 

See the [quick tutorial](tutorials/quick-start.html).

## News

<ul>
	{% for post in site.posts limit:3 %}
		<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
		{{ post.excerpt | strip_html | truncatewords:50 }}
		</li>
	{% endfor %}
</ul>

A list of all posts is available [here](blog.html).

## YouTube Channel

Videos and tutorials are available [here](https://www.youtube.com/channel/UCyFnEhd8rT7dUJCDP-UYYHA).


