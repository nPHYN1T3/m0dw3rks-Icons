m0dw3rks-Icons [ m0dw3rks.com ] My personal icons primarily for uncommon mimetypes and applications.

Right now the state of the set is incomplete, with several thousand needing to be done yet. There are lots of included icons that are uninspired or "roughed in" for now. I design things to fit what it represents rather than adhering to a cohesive style. This also lends itself to icons being easier to identify since not everything is a square or circle with something inside. Color and shape allow icons to stand out from each other. Hydraulic systems for compressed file formats, colored speakers for audio formats, "mix tapes" for playlist formats, tons of color variance for things like color coded ssh sessions, "sided" browser icons for multi-monitor setups, loose leaf and a pencil for text files, edge perf dot matrix print outs for log files and Satanic rituals for printers...am I right?!

2893 icons total from 16x16 to 512x512. Fair warning my focus is for dark themes. I have this strange aversion to staring into lamps all day...I mean monitors. While I typically focus on things I use, there are already a lot of things I don't use included in the set. I'm re-introducing the scalable versions. Beware that many with text are not converted to paths and may "explode" or look wrong if you don't have the font. In addition to the font issues many render wrong in general. Mesh gradients and various filters don't play nice outside Inkscape. (Small Preview Below)

As of May 2025 I may be curtailing things a bit. I've hit a number of road blocks for things such as:
- Keeping track of 10 icon names per application based on how a package was installed.
- Mimetypes I've never heard of with vague info on what it is for so I can't tell what it should symbolize. Looking at other icons sets has shown they either don't have an icon for the mime in question or it's vague and gives me nothing to go on.
- Keeping track of dead projects.
- Thousands of symbolic icons for which I don't need to reinvent the wheel.

So while the set is not complete, I will consider it complete/done unless I can find something I want to do or something I can get decent info on what it is for (mimetypes). Which is a fancy way of saying things will be a trickle from here on out.

# Installation
Unzip / Decompress or clone the git to either ~/.local/share/icons or /usr/share/icons for system wide use.
You may want to alter the index.theme file and set the Inherits value to your preferred fallback icon set to fill in potential gaps.

Copy, move or symlink the xml files in the xml folder to /usr/share/mime/packages/ and update your mime database.

(sudo|doas|run0) (cp|mv|ln -s) *.xml /usr/share/mime/packages/

(sudo|doas|run0) update-mime-database /usr/share/mime/

*If you notice included application icons that do not adhere to the theme it may be because they are pulling from /usr/share/pixmaps. If that is the case you will need to copy|symlink the desired png|xpm|svg from the icon set to the pixmaps location. (Looking at you XTerm...) KDE in general seems to ignore the application icons for me so extra rigamarole may be required.

CC BY-NC-ND 4.0

<img alt="A preview of some select icon files" title="A preview of some select icon files" text="A preview of some select icon files" src="ico-prev.jpg">

