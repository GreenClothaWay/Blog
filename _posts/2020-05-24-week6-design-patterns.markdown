---
layout: post
title:  "Week6: Design Patttern"
date:   2020-05-24 17:45:30 +0200
categories: update
---

Hi there,

In this post we present you our design pattern.
We implemented Decorater.
Decorator attach additional responsibilities to an object dynamically.
Click [here](https://sourcemaking.com/design_patterns/decorator) for more info.

This doesn't change anything in our class diagrams. So heres just on version.

[![Class_Diagram](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/classdiagram/account_forms_decorator.png)](https://raw.githubusercontent.com/GreenClothaWay/Website/master/doc/classdiagram/account_forms_decorator.png)


Normally, one would not have used any additional pattern in Django because you have lots of patterns allready implemented and write nearly no code.
The implentation you will find in our code is verx dirty and useless. But well, it was homework.

Enjoy the [before](https://github.com/GreenClothaWay/Website/blob/f450586dbaf45d877b487bf8f51b92c61a58223d/GreenClothaWay/src/account/forms.py#L7) and [after](https://github.com/GreenClothaWay/Website/blob/ad2b00a45193b75d9c821296dfb5065747a31ed2/GreenClothaWay/src/account/forms.py#L6) code.

Best regards,

The GreenClothaWay-Team
