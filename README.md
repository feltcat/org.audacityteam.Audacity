Flaptak notes
=============

`LV2_PATH` is set in a wrapper script because variable substitution
doesn't work.

`patches/audacity-suil-fix.patch` is necessary for suil (LV2 UI) to
work. A fix was submitted upstream in the past but was ignored.
This version of the patch is higly specific to flatpak.
