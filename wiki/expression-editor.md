---
layout: page
title: Expression Editor
permalink: /interface/expression-editor/
category: interface
---

The Expression Editor appears when you need to enter a value for an action or a condition. You will therefore get it when you are using the [event editor](/interface/event-editor/).
![](/wiki/assets/Screenshots/Expression_Editor.png)
 
The expression editor works like a big calculator. The current expression is displayed in the white edit zone and you can click any of the buttons to enter a new value.
The number buttons are used to enter numbers, and the function buttons to enter functions, like Sine and Cosine. Some functions ask for a parameter, the parameter is delimited by < and > and is automatically selected when you choose the function. Replace the content of < and > by the parameter. You can select the next < and > by clicking on the Next Parameter button. In [CF2.5], the button looks like this:![](/wiki/assets/Screenshots/Next_Parameter.png). In MMF2, the button looks like this: **Next**.
Some actions or conditions ask for text expressions: you then use strings enclosed in quotes like "This string", and the functions ending by $

## Retrieve data from object
This section is very important: it presents you with all the objects of the application. Click on one of the objects. This opens a popup menu presenting the possible expressions of the object: you just have to choose what value you need to retrieve from the object. Click on it, and a new function appears in the edit zone. In [CF2.5], this section is displayed below the edit area and most of the buttons, as shown above. In [MMF2], this section is a dialog box displayed by clicking the **Retrieve data from object** button.

## Check current expression
If "Valid expression" appears then your expression is correctly written. If "Syntax error" appears then you have made a mistake somewhere in your expression: carefully check every element of the expression to find it. In [MMF2], you need to click the **Check current expression** button. In [CF2.5], this happens automatically.

**This page was originally written by Advaith for the MediaWiki instance of ClickWiki and ported to EncycloFusion by TropicalBananas**

[CF2.5]: /fusion/2.5/
[MMF2]: /fusion/2.0/
