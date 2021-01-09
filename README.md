# doom-exwm-edwina

The Doom Config is held as an org file, I have tried to add as many relevant files as possible.

At the moment I'd suggest it's working with some additional libs/func to help place floating frames.

_EXWM Specific_
By selecting the window you can with the keyboard move a floating frame to another location. 

Minimal checks are performed as it's very much a work in progress.

I have added in the lib the ability to place and size a EXWM frame at a specific location
and size.

Built on top of this is another function to place any floating windows at a specific compass location.

_Edwina Specific_
Edwina was added to see if it added value.

Edwina seems to be preventing some of the doom buffers from showing up so I have added in a filter of what is handled by Edwina and doom.

To Use the modified version of Edwina within Doom you will need to add

*(package! edwina :recipe (:host github :repo "glencjones/edwina") )*

Currently I have created a map using the Doom macros, that works well when not in exwm, again remember you have the evil window functions too.

_Conclusion_
Early days with my Lisp so don't expect too much, I'm sure it will get better.

A rather strange use of if-statements to switch in and out the sections of the exwm using the TERM type.  You can find the integration of the 
X windows code/files included.  Reminder I use term type to switch on and off exwm.  you could also do this on the command line.

Like I say a bit rough first cut, will try to improve documentation as I go.

I have an open opinion at the moment as currently I have 3 navigation: std doom, exwm and Edwina all as far as I can see doing
the same thing.   I have set up Edwina to work both in doom only and X.  So it's questionable if the maps for Edwina need to be used.

will revisit EXWM, Doom and Edwina navigation maps to merge them.

_State_
Very much a Beta release, as I have left some logging in.
