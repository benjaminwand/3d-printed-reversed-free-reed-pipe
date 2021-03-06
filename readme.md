# 3d-printed reversed free reed pipe

## General
This is a collection of FreeCAD files that will help you to 3D-print a part of a new type of organ pipe (the mechanism was patented in 1993 by Ernst Zacharias, Hohner), to be used with one or two piece(s) of tube. 

Please start by adding the desired measurements into the spreadsheet. Then export the upper and lower part separately for printing.

The point of ‘pitch tester’ is having it easier to figure out which reed you hold in your hands. It works best using a reed a little bit lower (1-3 semitones) than the resonator. You probably only need one, or one per person (hygienic reasons).

[There are flue pipes as well.](https://github.com/benjaminwand/3d-printed-labial-pipe)

I'd be happy to hear about your instrument!

Licensed under CC-BY <br>
https://creativecommons.org/licenses/by/4.0/legalcode

## Versions
0.1 reed somewhere in the middle of the tube <br>
0.2 reed at the end of the tube, blowing directly into the tube <br>
0.3 reed at the end of the tube, traverse-flute-like <br>

## Reeds testing
Mac: ffmpeg -f avfoundation -i ":0" -filter_complex "showcqt" -c:v rawvideo -c:a pcm_s16le -pix_fmt yuv422p -f matroska - | mpv -
Linux: ffmpeg -f alsa -i hw:0 -filter_complex "showcqt" -c:v rawvideo -c:a pcm_s16le -pix_fmt yuv422p -f matroska - | mpv -

## Texts about reversed reed pipes (German only)
* Ernst Zacharias: “Die dynamische Orgel”. Instrumentenbau-Zeitschrift 1999, Heft 7-8, S. 26
* Ernst Zacharias: “Die dynamische Orgel”. Ars Organi 50, 2002, H. 1, S. 19-21
* Ernst Zacharias: “Eine Orgel mit Tastendynamik”. Ars Organi 51, 2003, H. 1, S. 47-48
* Ernst Zacharias: “Die Dynamik der Orgel”. Ars Organi 54, 2006, H. 2, S. 112-113
* Mathias Jung: Die Durchschlagzungen der neuen Rohlf-Orgel für die Marktkirche in Hamburg-Poppenbüttel. ISO Journal N° 25, März 2007. Im Internet auf http://www.orgelbau-rohlf.de/themen/pdf/Poppenbuettel-Hochdruckwerk.pdf
* Mathias Jung: “”Die Zacharias- Zunge in Eckenhaid. Im Internet eingestellt unter: http://www.orgelbau-rohlf.de/themen/pdf/Zachariaszunge.pdf

## Multimedia
* http://vimeo.com/39074251 talking about free reed stops after 7:50
* http://www.friedenskirche-eckenhaid.de/media/CD-Downloads/Friedenspiel_pour_le_temps.mp3 
* https://www.youtube.com/watch?v=3jkmdJ6xWm4 Ernst Zacharias with straight inverted free reed pipe, recorded 2017
* my first attempt with 0.1 https://www.youtube.com/watch?v=mxvTzLA2iDw
