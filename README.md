# doom-exwm


The Doom Config is held as an org file, I have tried to add as many relevant files as possible.

At the moment I'd suggest it's working with some additonal libs/func to help place floating frames.

By selecting the window you can with the keyboard move a floating frame to another location. 

Minimal checks are performed as it's very much a work in progress.  Edwina was added to see if it added value.

I have an open opinion at the moment as currently I have 3 navigations std doom, exwm and edwina all as far as I can see doing
the same thing.   I have set up Edwina to work both in doom only and X.  So it's questionable if the maps for Edwina need to be used.

Currently I have created a map using the Doom macros, that works well when not in exwm, again you have the evil window functions.

Early days with my Lisp so dont expect too much, I'm sure it will get better.

A rather strange use of if-statements to switch in and out the sections of the exwm using the TERM type.  You can find the integration of the 
X windows code/files included.  Reminder I use term type to switch on and off exwm.  you could also do this on the command line.

Like I say a bit rough first cut, will try to improve documentation as I go.

will revisit EXWM, Doom and Edwina navigation maps to merge them.
