MMFCompat.cox: Multimedia Fusion 1.x object-name compatibility fix
Created by Joshtek, revised by TropicalBananas, and published by the EncycloFusion project.
------------------------------------------------------------------

This extension fixes a compatibility bug with Multimedia Fusion 1.x versions
on modern Windows where renaming an object in the editor can cause an object's
name to appear corruped with garbage characters after it if the object's name
is shorter than the previous name. Inserting the extension as an object into
the CCA is not necessary, the bug is only present in the editor.

In this way, this extension is somewhat different from other MMF extensions,
because it is just a bug fix for the editor that utilizes the extension API
to fix it.

It has been tested against MMF 1.0 Build 87, MMF 1.2 Build 98, MMF 1.5 Build 105,
and MMF 1.5 Build 119, but it should work with any release of Multimedia Fusion 1.x
on modern Windows. Should a MMF build that is incompatible with this extension be
encountered, it will fail safely, silently, and make no changes.

----------------------
Installing the bug-fix
----------------------
Just drop MMFCompat.cox into your Multimedia Fusion Extensions folder, and when
time you start up Multimedia Fusion, the bug will already be fixed as long as
the extension is present in the Extensions folder.

You do not need to put it in the Data\Runtime folder and you do not need to
insert the extension into your CCA, just having it in the Extensions folder is
sufficient to fix the bug. If you do attempt to insert the extension as an object
in your CCA, it will not be inserted and it will not do anything.

----------------------------------
Building MMFCompat.cox from source
----------------------------------
For this, you can use clang or Visual C++ 4.x, other versions of Visual C++ have
not been tested with this.

Building with clang:
  First make sure you have clang and LLVM present in your Windows path.
  Then, enter the source directory and then run build.bat.
  This should build the MMFCompat.cox successfully.  

Building with Visual C++ 4.x:
  Open MMFcompat.mdp as a workspace in Microsoft Developer Studio, and press the Build button.
  This should build the MMFCompat.cox successfully.  
