---
layout: page
title: TGF GAM/C&C CCA
permalink: /file-extensions/GAM-CCA/
category: file-extensions
---

{% include thumbnail image = "/wiki/assets/Clickteam/Filetypes/GAMCCA.png" text = "File icons, .GAM on the bottom layer and .CCA on the top layer" %}

**TGF GAM/C&C CCA** (The Games Factory Save File/Click & Create Application) is the file format used by [The Games Factory]
and [Click & Create]. Both [TGF]'s .gam [C&C]'s .cca use a nearly identical format and are intercompatible. As with a [MFA]
file, the developer's events, frames and sprites are stored inside the file, and acts as the "source code" to the
user's game.

The Games Factory and Click & Create's successor products can import data to a newer
format, but cannot save back to a [TGF] gam or [C&C] cca. Protected GAM files cannot be opened. Samples
and music (MIDI) can be imported from the load dialog box by selecting this file type.

{% include TOC %}

## Protected GAM/CCA Files
When the user decides to export their creation, they have an option labelled
"Protect Game". This prevents the GAM/CCA file alongside the stand alone executable/setup
program from being opened in the editor. If attempted, the user will be greeted with
the message "This is not an application file!" (in [C&C]) "Cannot open protected GAM file" (in [TGF])
or "Cannot read a protected TGF or C&C." (in MMF and up)

Historically, it was possible to contact Clickteam to unlock the file. However, as
one of the developer's hard drives failed, the utility has been lost.

## Upgrading to MFA
It is possible to upgrade older GAM/CCA files to the newer, [MFA] format by importing
them into [MMF]. This then allows you to export your assets (sounds, images etc)
as well as viewing events and frames. However, it should be noted the game may
not behave as expected as the runtime has greatly changed since the time of
The Games Factory and Click & Create. For example, in TGF1 the "Hide mouse pointer"
action would hide the mouse pointer for just that frame, but in MMF2, this would hide
throughout the entire application until the action "Show mouse pointer" occurs.

## Limitations
Not documented.

## Bugs
Not documented.

[Multimedia Fusion]: /fusion/
[MMF]: /fusion/
[MFA]: /file-extensions/MFA/
[The Games Factory]: /games-factory/
[TGF]: /games-factory/
[Click & Create]: /click-and-create/
[C&C]: /click-and-create/
