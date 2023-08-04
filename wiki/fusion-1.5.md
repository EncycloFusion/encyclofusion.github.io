---
layout: product
title: Multimedia Fusion 1.5
permalink: /fusion/1.5/
category: fusion

image: "/wiki/assets/Screenshots/MMF1.jpg"
image_caption: "Version 1.5 running on Windows 98."
developer: "[Clickteam](/clickteam/)"
status: "Obsolete"
initial_release_build: "v1.0"
initial_release_date: "1998"
last_stable_build: "Build 119"
last_stable_date: "2005"
last_beta_build: null
last_beta_date: null
predecessor: "[Click and Create](/click-and-create/)"
successor: "[Multimedia Fusion 2](/fusion/2.0/)"
platforms:
  - windows
languages:
  - en
  - fr
shop_link: null
support_link: null
links:
  - "[Retired Products Downloads](http://www.clickteam.com/download-centre/retired-products)"
---

**Multimedia Fusion**, or as commonly referred to as **MMF** or **MMF1.5**
(depending on the version at the time) is the successor product to [Click and Create]
and [The Games Factory] developed by [Clickteam]. The software has had a long run of 8 years,
before it was succeeded by [Multimedia Fusion 2].

{% include TOC %}

{% include thumbnail
    image = "/wiki/assets/Clickteam/Icon MMF1.5.png"
    text = "Program Icon"
%}

## Editions

#### Standard
Not documented.

#### Pro
Not documented.

## Versions

#### Version 1.0
Not documented.

#### Version 1.2
Not documented.

#### Version 1.5
Not documented.

## Guides

#### MMF on Windows 11/10
On Windows 11, when running Multimedia Fusion 1.5 or 1.2 on the latest version, the application hangs at the splash screen.
This is caused by 2 problematic files in the extensions folder:

**kcqtvr.cox**

**kcqtw.cox**

When these files are removed from the extension folder in MMF 1.5 or 1.2, they launch fine on Windows 11 and should work the same on Windows 10.
This will allow Multimedia Fusion 1.5 or 1.2 to run, however, occasionally when you try to rename something, you might notice a problem:

##### Garbage characters
{% include thumbnail
    image "/wiki/assets/Screenshots/garbagechars.png"
    text = "Program Icon"
%}
See all that gibberish after the text “test”? those are called garbage characters, and we don’t want those there.

But this problem’s solution is rather simple, all you have to do is **apply compatibility mode** for Windows Vista, 7 or 8 to **MMFUSION.EXE**.

Ideally you would choose Windows 7 or 8, as Vista’s compatibility mode causes visual problems with the taskbar, but it will still work.

#### MMF on Windows 7/Vista
The following extension is incompatible with Aero:

**kcqtw3.cox**

It hangs the application on Windows Vista and 7, but doesn’t on Windows 11.

[Clickteam]: /clickteam/
[Click and Create]: /click-and-create/
[Multimedia Fusion 2]: /fusion/2.0/
[The Games Factory]: /games-factory/
