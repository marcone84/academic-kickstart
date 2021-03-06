---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Sankey Networks of Far-right Radicalization Pathways"
subtitle: ""
summary: ""
authors: [Marcus Mann]
tags: []
categories: []
date: 2020-06-22T16:48:17-04:00
lastmod: 2020-06-22T16:48:17-04:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Recently, I was given the chance to explore an online forum where subscribers to a neo-nazi website were sharing the media sources, groups, movements, and thinkers that were responsible for bringing them there. Better yet, participants in this forum were sharing their journeys chronoligically, mapping out for anyone that might be interested, the sources they consumed as their beliefs became more extreme. There is more information on these data [here](https://www.splcenter.org/20180419/mcinnes-molyneux-and-4chan-investigating-pathways-alt-right). 

Now, these data are by no means representative of broader pathways to far-right beliefs. There are only 44 testimonies shared here and there are obvious selection issues given that this is only one website, these are only the posters on that website, and the website itself is a very specific brand of far-right beliefs (i.e. Nazism). However, there are notable consistencies between accounts in these data and accounts themselves were sincere and often detailed. 

Below are interactive Sankey Networks that these accounts of radicalization render. You can scroll over pathways or nodes to highlight exactly what nodes are connected in these testimonies.

The first network is using the full data and the second is using only the sources that were mentioned more than once. All testimonies in the first network end with arriving at one of two neo-nazi sites: The Daily Stormer or The Right Stuff. I grouped these together because 1) all testimonies ended with one of these and 2) it is generally agreed that these sites, though not always on the same page, represent some termination point of an online radicalization process. In the second graph, since I eliminated all sources that were mentioned only once, this also eliminated sources that were connected to The Daily Stormer or The Right Stuff. Therefore, we see paths that don't end this way, although all connections represent reported paths at  some point in this process. Most interesting about this graph is that three major pathways emerge: an "alt-light" to "alt-right" pathway (e.g. Joe Rogan -> Gavin McInnese), a Libertarian pathway (e.g. Ron Paul -> Pat Buchanan), and an atheist/skeptic pathway (e.g. Sam Harris -> Ben Shapiro).  


## Interactive Sankey Network of all Radicalization Pathways Reported
<div id="htmlwidget_container">
  <div id="htmlwidget-3611dc89ad4d4a488973" style="width:720px;height:500px;" class="sankeyNetwork html-widget"></div>
</div>
<script type="application/json" data-for="htmlwidget-3611dc89ad4d4a488973">{"x":{"links":{"source":[59,7,37,34,20,36,2,31,4,45,0,43,72,57,55,58,7,72,29,73,0,11,15,4,66,62,3,21,54,53,32,11,0,17,13,18,72,65,30,3,4,13,11,9,7,48,71,71,1,7,46,34,70,2,17,44,64,3,55,56,35,18,67,71,72,22,69,3,13,5,3,7,51,13,4,2,4,25,47,28,66,74,51,61,0,0,40,4,11,12,63,42,16,39,68,4,19,21,55,0,33,49,60,7,27,3,41,38,23,24,26,52,8,10,16,19,44,33,14,4,50],"target":[0,0,0,0,0,0,0,0,0,34,1,58,46,22,37,9,35,47,53,2,2,13,13,13,13,13,23,26,57,3,3,3,3,3,3,3,48,21,21,21,18,18,28,11,11,25,44,45,8,8,7,7,7,7,7,31,16,16,38,55,12,27,33,33,49,10,41,19,19,19,24,24,24,20,50,17,17,30,15,4,4,4,4,4,4,5,51,51,29,39,14,56,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,6,40,36,42,32,32,54,52,43],"value":[1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2,1,1,1,2,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,1,1,1,1,1,2,2,1,2,1,1,1,1,1,1,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,2,1,1,1,4,2,1,7,1,1,1,1,1,4,1,1,1,4,1,1,3,1,1,1,1,1,1,1,1]},"nodes":{"name":["/pol/","Aurini","GamerGate","Jared Taylor","Stefan Molyneux","Steven Crowder","The Right Stuff or Daily Stormer","Milo Yiannopoulos","Millenial Woes","Britanny Pettibone & Tara McCarthy","Paul Waggoner","Lauren Southern","Natt Danelaw","Gavin McInnes","The Art of Manliness","Southern Avenger","Morrakiu","Sargon of Akkad","Jim Goad","Red Ice","Ricky Vaughn","Jayman and Sailer","Blaire White","Greg Johnson","Richard Spencer","Lesswrong","Gregory Cochran","Nick Fuentes","Jordan Peterson","Suidlanders","SlateStarCodex","mises.com","Vdare","Pat Buchanan","/r/The_Donald","Christopher Cantwell","Tyrant Fashister","Bre Fachex & Mark Collet","Mr. Bond","Sven Songs","Tim Pool","Radio Aryan","Varg","Warski","Lew Rockwell","Manosphere","Ben Shapiro","Doug Stanhope","Jaron Lanier","Paul Kersey","Roaming Millenial","Styx HexenHammer666","Walt Bismarck","Dreamy Diglot","VICE","Murdoch Murdoch","The Golden One","Jack Donovan","Aydin Paladin","/b/","Alex Jones","Bill Whittle","Dave Rubin","Derrick Jensen","Encyclopedia Dramatica","Hans-Hermann Hoppe","Joe Rogan","Lou Dobbs","Opie and Anthony","Pewdiepie","PJ Watson","Ron Paul","Sam Harris","Tea Party","The Drunken Peasants"],"group":["/pol/","Aurini","GamerGate","Jared Taylor","Stefan Molyneux","Steven Crowder","The Right Stuff or Daily Stormer","Milo Yiannopoulos","Millenial Woes","Britanny Pettibone & Tara McCarthy","Paul Waggoner","Lauren Southern","Natt Danelaw","Gavin McInnes","The Art of Manliness","Southern Avenger","Morrakiu","Sargon of Akkad","Jim Goad","Red Ice","Ricky Vaughn","Jayman and Sailer","Blaire White","Greg Johnson","Richard Spencer","Lesswrong","Gregory Cochran","Nick Fuentes","Jordan Peterson","Suidlanders","SlateStarCodex","mises.com","Vdare","Pat Buchanan","/r/The_Donald","Christopher Cantwell","Tyrant Fashister","Bre Fachex & Mark Collet","Mr. Bond","Sven Songs","Tim Pool","Radio Aryan","Varg","Warski","Lew Rockwell","Manosphere","Ben Shapiro","Doug Stanhope","Jaron Lanier","Paul Kersey","Roaming Millenial","Styx HexenHammer666","Walt Bismarck","Dreamy Diglot","VICE","Murdoch Murdoch","The Golden One","Jack Donovan","Aydin Paladin","/b/","Alex Jones","Bill Whittle","Dave Rubin","Derrick Jensen","Encyclopedia Dramatica","Hans-Hermann Hoppe","Joe Rogan","Lou Dobbs","Opie and Anthony","Pewdiepie","PJ Watson","Ron Paul","Sam Harris","Tea Party","The Drunken Peasants"]},"options":{"NodeID":"name","NodeGroup":"name","LinkGroup":null,"colourScale":"d3.scaleOrdinal(d3.schemeCategory20);","fontSize":12,"fontFamily":null,"nodeWidth":30,"nodePadding":10,"units":"TWh","margin":{"top":null,"right":null,"bottom":null,"left":null},"iterations":32,"sinksRight":true}},"evals":[],"jsHooks":[]}</script>
<script type="application/htmlwidget-sizing" data-for="htmlwidget-3611dc89ad4d4a488973">{"viewer":{"width":450,"height":350,"padding":10,"fill":true},"browser":{"width":1440,"height":1000,"padding":10,"fill":false}}</script>


## Interactive Sankey Network of Radicalization Pathways with Sources Mentioned More than Once
<div id="htmlwidget_container">
  <div id="htmlwidget-ba1bf9adb44b635468ff" style="width:960px;height:500px;" class="sankeyNetwork html-widget"></div>
</div>
<script type="application/json" data-for="htmlwidget-ba1bf9adb44b635468ff">{"x":{"links":{"source":[3,7,40,1,6,44,42,7,44,6,3,41,24,2,13,6,8,9,18,24,44,2,18,3,24,7,43,43,7,1,8,40,30,2,42,9,43,44,2,18,7,38,2,18,3,1,3,6,41,38,6,3,24,6,7,13,32,2,10,42,14,3,14,10,30,32,3],"target":[6,6,6,6,0,33,27,23,34,1,18,18,18,12,16,2,2,2,2,2,35,13,9,9,19,24,30,31,25,7,7,7,21,14,28,17,32,36,10,10,15,15,15,11,37,8,8,3,3,3,4,38,20,5,5,5,5,5,5,5,5,5,26,29,22,22,39],"value":[1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,1,1,1,1,2,1,1,1,1,1,1,1,2,2,1,1,2,1,1,1,1,2,1,1,1,1,1,7,1,2,1,4,4,1,2,1,1,1,1,1,1]},"nodes":{"name":["Aurini","GamerGate","Jared Taylor","Stefan Molyneux","Steven Crowder","The Right Stuff or Daily Stormer","/pol/","Milo Yiannopoulos","Sargon of Akkad","Jim Goad","Red Ice","Ricky Vaughn","Greg Johnson","Jayman and Sailer","Morrakiu","Richard Spencer","Gregory Cochran","Nick Fuentes","Gavin McInnes","Jordan Peterson","Suidlanders","mises.com","Vdare","Christopher Cantwell","Lauren Southern","Millenial Woes","Tyrant Fashister","Bre Fachex & Mark Collet","Mr. Bond","Varg","Lew Rockwell","Manosphere","Pat Buchanan","Ben Shapiro","Doug Stanhope","Jaron Lanier","Paul Kersey","Roaming Millenial","Styx HexenHammer666","Walt Bismarck","/r/The_Donald","Joe Rogan","Murdoch Murdoch","Ron Paul","Sam Harris"],"group":["Aurini","GamerGate","Jared Taylor","Stefan Molyneux","Steven Crowder","The Right Stuff or Daily Stormer","/pol/","Milo Yiannopoulos","Sargon of Akkad","Jim Goad","Red Ice","Ricky Vaughn","Greg Johnson","Jayman and Sailer","Morrakiu","Richard Spencer","Gregory Cochran","Nick Fuentes","Gavin McInnes","Jordan Peterson","Suidlanders","mises.com","Vdare","Christopher Cantwell","Lauren Southern","Millenial Woes","Tyrant Fashister","Bre Fachex & Mark Collet","Mr. Bond","Varg","Lew Rockwell","Manosphere","Pat Buchanan","Ben Shapiro","Doug Stanhope","Jaron Lanier","Paul Kersey","Roaming Millenial","Styx HexenHammer666","Walt Bismarck","/r/The_Donald","Joe Rogan","Murdoch Murdoch","Ron Paul","Sam Harris"]},"options":{"NodeID":"name","NodeGroup":"name","LinkGroup":null,"colourScale":"d3.scaleOrdinal(d3.schemeCategory20);","fontSize":12,"fontFamily":null,"nodeWidth":30,"nodePadding":10,"units":"TWh","margin":{"top":null,"right":null,"bottom":null,"left":null},"iterations":32,"sinksRight":true}},"evals":[],"jsHooks":[]}</script>
<script type="application/htmlwidget-sizing" data-for="htmlwidget-ba1bf9adb44b635468ff">{"viewer":{"width":450,"height":350,"padding":10,"fill":true},"browser":{"width":1440,"height":1000,"padding":10,"fill":false}}</script>

## Twitter Thread on these graphs
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">In light of this news, it just so happens that I have been playing with some data on pathways of far-right radicalization the past couple days. So what does deplatforming Gavin McInnes mean in terms of peoples&#39; pathways to the alt-right? <a href="https://t.co/ZpvXjbhRSn">https://t.co/ZpvXjbhRSn</a></p>&mdash; Marcus Mann (@MannMarcus) <a href="https://twitter.com/MannMarcus/status/1275498334992678912?ref_src=twsrc%5Etfw">June 23,ch 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
