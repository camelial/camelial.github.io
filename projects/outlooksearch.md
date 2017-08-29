---
layout: project
type: project
image: images/micromouse.jpg
title: Microsoft Outlook Project Search Tool
permalink: projects/outlooksearch
date: 2017
labels:
  - Microsoft
  - Outlook
  - C#
summary: I developed a Microsoft Outlook add-in to help engineers at my workplace quickly find and organize their projects in their inboxes and conveniently access their respective folders.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

For my internship at Kai Hawaii, I developed an add-in for the company's Microsoft Outlook inboxes. The engineers recieve and send many emails regarding different engineering projects, and store many files related to specific projects on the network folders. The add-in that I developed makes it easy for the engineers to search for project folders on the network and in their inboxes, as well as organize their emails related to specific projects into shared project email folders to keept their inboxes clean and organized. The add-in includes a search tool to search for folders by project names or numbers, a move tool for filing emails into folders, and a favorites list for easy access to frequently used folders.

For this project, I was responsible for finding the most efficient way to search through the thousands of project folders, such that the add-in would not be disabled by Outlook for taking too long. My solution involved storing the users' file data on a text file on their computer, and accessing that file instead of searching through every folder every time. I created a simple searching algorithm to search through the contents of the data file. The end result was a very quick and simple searching tool that the company finds very useful. 



