---
title: User Stories Tool - Plugin for Eclipse
date: 2016-02-27
layout: page
permalink: /projects/ustool/legacy
exclude_from_nav: true
---

User Stories Tool - Plugin for Eclipse  
developed by [Kristo Koci](https://github.com/crazedkiller) and [Theodoros Kyriazidis](https://github.com/theokyr)

What it is
=======

The User Stories Tool is a plugin that allows developers to add real-time Requirement Traceability to their code.


Features
=======

* Manage and Categorize User Stories (Requirements)
* View and Search User Stories
* Manage Actors (Users)
* Create Links (Traces) to code with an easy to use menu or manually by using the auto-complete feature

Installation
=======

1\. Copy com.plugin.userstories_0.1.0.jar into your eclipse/plugins/ or eclipse/dropins/plugins directory  
2\. Add UserStoryLink.jar to every project where you want the User Stories Tool to be integrated (Right Click Project > Java Build Path > Libaries > Add External JARs)  

![Installation of UserStoryLink]({{ site.url }}/images/ustool/legacy/us_jar.PNG)

3\. Open the Requirements Tree View from Eclipse (Window > Show View > Other > User Stories > Requirements Tree)  


![Select View]({{ site.url }}/images/ustool/legacy/us_openview_1.png)
![Open Tree]({{ site.url }}/images/ustool/legacy/us_openview_2.png)

4\. Select your project from the Dropdown (located right below the "Requirements Tree" tab)  
5\. You're ready!  

Screenshots
=======

![Requirements Tree]({{ site.url }}/images/ustool/legacy/us_reqtree.png)

*Requirements Tree*

---------------------------------------  

![Table]({{ site.url }}/images/ustool/legacy/us_table.png)

*Selected Requirement Viewer*

---------------------------------------  

![Requirements Editor]({{ site.url }}/images/ustool/legacy/us_editor.png)

*Requirements Editor*

---------------------------------------  

![Link Creator]({{ site.url }}/images/ustool/legacy/us_linkmanager.png)

*Usage of Link Creator*

---------------------------------------  

![Autocomplete 1]({{ site.url }}/images/ustool/legacy/us_autocomplete_1.png)
![Autocomplete 2]({{ site.url }}/images/ustool/legacy/us_autocomplete_2.png)

*Usage of Auto-Complete*

---------------------------------------  

![Actor Manager]({{ site.url }}/images/ustool/legacy/us_actormanager.png)

*Usage of Actor Manager*

Feedback
=======
Please email us at theo.kyrr@gmail.com and xristoskotsis1@hotmail.com with all your feedback!

If you find a bug, apart from including reproduction steps, it would be massive help to attach the UserStoriesLog file.
It is located in: project path/userstories/USToolSettings/UserStoriesLog.txt
