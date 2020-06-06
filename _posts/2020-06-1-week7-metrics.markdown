---
layout: post
title:  "Week7: Metrics"
date:   2020-06-1 17:45:30 +0200
categories: update
---

Hi there,

this Week is about metrics.

Goals of metrics: [![Goals](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/metrics_goals.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/metrics_goals.png)

First we calculated the Halstead-Metric for our file [account/views.py](https://github.com/GreenClothaWay/Website/blob/master/GreenClothaWay/src/account/views.py). For this we used a python tool named [multimetric](https://pypi.org/project/multimetric/).

[![Multi_Metric](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/multimetric_tool_result.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/multimetric_tool_result.png)

TBH 85 seems like a pretty bad value BUT the file most definitely is a pretty normal Django file so we decided not to change anything. We didnt even find places to change something.



Afterwards we integrated [codacy](https://www.codacy.com/) to our repository. Its already integrated in our Github Actions which get triggerred by a pull request to master.

[![codacy_in_action](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_in_action.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_in_action.png)

Codacy had some issues that weren't actual issues. so we decided not to work on them. You can see some of them in the picture below.

[![Issue_not_issue](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/metrics_not_to_work_on_2.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/metrics_not_to_work_on_2.png)

For example this docstring is not needed.

[![before_issues](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/issues_before.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/issues_before.png)

We worked on some real issues tho. One example is shown below.

[![issues](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_issue.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_issue.png)

Here you can find the [before](https://github.com/GreenClothaWay/Website/blob/555daf5030346d1966e6dab3c2d0d24d22dbe6db/GreenClothaWay/src/inseration/forms.py#L23)  and the [after](https://github.com/GreenClothaWay/Website/blob/0d2fba37af2cfad1ab80d1530e164c31c6e2ad31/GreenClothaWay/src/inseration/forms.py#L23) code. A rather simple issue.

We also fixed some unused imports. After our work codacy shows us what we have fixed.
[![fixed_issues](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_fixed_issues.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/codacy_fixed_issues.png)

[![after_issues](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/issues_after.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/screenshots/issues_after.png)

Best regards,

The GreenClothaWay-Team
