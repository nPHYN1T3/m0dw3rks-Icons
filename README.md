m0dw3rks-Icons [ m0dw3rks.com ] My personal icons primarily for uncommon mimetypes and applications.

Right now the state of the set is incomplete, with several thousand needing to be done yet. There are lots of included icons that are uninspired or "roughed in" for now. I design things to fit what it represents rather than adhering to a cohesive style. This also lends itself to icons being easier to identify since not everything is a square or circle with something inside. Color and shape allow icons to stand out from each other. Hydraulic systems for compressed file formats, colored speakers for audio formats, "mix tapes" for playlist formats, tons of color variance for things like color coded ssh sessions, "sided" browser icons for multi-monitor setups, loose leaf and a pencil for text files, edge perf dot matrix print outs for log files and Satanic rituals for printers...am I right?!

2835 icons total from 16x16 to 512x512. (Only 6,000,000 left) Fair warning my focus is for dark themes. I have this strange aversion to staring into lamps all day...I mean monitors. While I typically focus on things I use, there are already a lot of things I don't use included in the set. I'm re-introducing the scalable versions. Beware that many with text are not converted to paths and may "explode" or look wrong if you don't have the font. In addition to the font issues many render wrong in general. Mesh gradients and various filters don't play nice outside Inkscape. (Small Preview Below)

As of May 2025 I may be curtailing things a bit. I may try to just focus on system icons (actions/panel/places/devices/mime) from here on out. The backport cruft of old icon names combined the stupidity of one application having 12 icon names for the same icon because of installation method is more than I care to keep track of. Toss in keeping up with what is or isn't a dead project/application and things are just an overgrowth of issues. There is also the issue of all the com.stupid, org.stupid, net.stupid and io.stupid naming which is pointless, painful and...stupid. This feels like "Say what you mean!" This is an icon for "coolapplication" not "(org|net|com|io).(lab|hub|io|sf).(snapd|flatpak|apt|aur|dnf|emerge|pkgsrc).authorname.authorwebsite.coolapplication."

On the note of cruft and confusion, open an issue if you find an icons state is wrong or if a state is missing. For example various battery/power things, perhaps the charge is right but power mode is wrong. Perhaps you notice the icons for network connected and disconnected are there but some other mode is absent. There are far too many icons for the same thing in conjunction with something that is obscure, unclear or ambiguous that can lead to it being missed as I simply don't know what uses it, where it will be displayed or what it is even to represent.

# Installation
Unzip / Decompress or clone the git to either ~/.local/share/icons or /usr/share/icons for system wide use.
You may want to alter the index.theme file and set the Inherits value to your preferred fallback icon set to fill in potential gaps.

Copy, move or symlink the xml files in the xml folder to /usr/share/mime/packages/ and update your mime database.

(sudo|doas|run0) (cp|mv|ln -s) *.xml /usr/share/mime/packages/

(sudo|doas|run0) update-mime-database /usr/share/mime/

*If you notice included application icons that do not adhere to the theme it may be because they are pulling from /usr/share/pixmaps. If that is the case you will need to copy|symlink the desired png|xpm|svg from the icon set to the pixmaps location. (Looking at you XTerm...) KDE in general seems to ignore the application icons for me so extra rigamarole may be required.

CC BY-NC-ND 4.0

<img alt="A preview of some select icon files" title="A preview of some select icon files" text="A preview of some select icon files" src="ico-prev.jpg">

