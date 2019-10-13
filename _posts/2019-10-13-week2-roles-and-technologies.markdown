---
layout: post
title:  "Week2: Roles and technologies"
date:   2019-10-13 21:11:26 +0200
categories: update
---

Hi there,

Firstly, we defined our roles for each contributor.

| Rup Role                |    Description                                                                            |      Assignee 
| :---                    |    :---                                                                                   |          :--- 
| Business Desginer       | Details a single set of business use cases                                                | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Requirement Specifier   | Details a single set of requirement use cases                                             | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Designer – Frontend     | Details the analysis and design for a single set of use cases which are frontend related  | Nico Diefenbacher
| Designer – Backend      | Details the analysis and design for a single set of use cases which are backend related   | Zeno Berkhan, Paul Meyer
| Test Designer – Frontend| Implements automated portions of the test design for the iteration concerning the frontend| Nico Diefenbacher, Zeno Berkhan|
| Test Designer – Backend | Implements automated portions of the test design for the iteration concerning the backend | Nico Diefenbacher, Paul Meyer
| Blog Writer             | 	Writes blog entries to keep people up to date                                           | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Project Manager         | Plans, tracks, and manages risk for a single iteration                                    | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Tool Specialist         | Is responsible for promoting and supporting Scrum| git status                             | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Deployment Manager      |  Specialist	Creates guidelines for using a specific tool                                  | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Configuration Manager   | Creates a deployment unit, reports on configuration status, performs audits, and so forth | Nico Diefenbacher, Zeno Berkhan, Paul Meyer
| Tool Specialist         |  Manager	Reviews and manages change requests                                             | Paul Meyer|
| Change Control Manager  | Reviews and manages change requests                                                       | Nico Diefenbacher, Zeno Berkhan, Paul Meyer

After we defined roles for each contributor, we thought 
In order to host our website we needed a server. After buying a server at Hetzner we installed a debian distribution and configured the servers ssh port. Otherwise it would have been under attack all the time. 

Furthermore we discussed about technical requirements such as firewalls and certificates. 

Afterwards we configured a simple firewall using shorewall. Following we installed a nginx webserver and requested a certificate from Lets Encrypt using certbot.


Best regards,

The GreenClothaWay-Team
