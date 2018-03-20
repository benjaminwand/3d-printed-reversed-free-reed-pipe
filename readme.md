# 3d-printed reversed free reed pipe

## General
This is a collection of FreeCAD files that will help you to 3D-print a part of a new type of organ pipe (the mechanism was patented in 1993 by Ernst Zacharias, Hohner), to be used with two pieces of tube. 

Please start by adding the desired measurements into the spreadsheet. Then export the upper and lower part separately for printing.

The point of ‘reed tester’ is having it easier to figure out which reed you hold in your hands, because it is a good idea using a reed a little bit lower (1-3 semitones) than the resonator. You probably only need one, ore one per person (hygienic reasons).

I'd be happy to hear about your instrument!

## Versions
(placeholder)

## Reeds testing
Mac: ffmpeg -f avfoundation -i ":0" -filter_complex "showcqt" -c:v rawvideo -c:a pcm_s16le -pix_fmt yuv422p -f matroska - | mpv -
Linux: ffmpeg -f alsa -i hw:0 -filter_complex "showcqt" -c:v rawvideo -c:a pcm_s16le -pix_fmt yuv422p -f matroska - | mpv -

## More about reversed reed pipes (German only)
* Ernst Zacharias: “Die dynamische Orgel”. Instrumentenbau-Zeitschrift 1999, Heft 7-8, S. 26
* Ernst Zacharias: “Die dynamische Orgel”. Ars Organi 50, 2002, H. 1, S. 19-21
* Ernst Zacharias: “Eine Orgel mit Tastendynamik”. Ars Organi 51, 2003, H. 1, S. 47-48
* Ernst Zacharias: “Die Dynamik der Orgel”. Ars Organi 54, 2006, H. 2, S. 112-113
* Mathias Jung: Die Durchschlagzungen der neuen Rohlf-Orgel für die Marktkirche in Hamburg-Poppenbüttel. ISO Journal N° 25, März 2007. Im Internet auf http://www.orgelbau-rohlf.de/themen/pdf/Poppenbuettel-Hochdruckwerk.pdf
* Mathias Jung: “”Die Zacharias- Zunge in Eckenhaid. Im Internet eingestellt unter: http://www.orgelbau-rohlf.de/themen/pdf/Zachariaszunge.pdf
* http://vimeo.com/39074251, gesehen am 20.3.2018. Ab 7:50 wird in diesem Video auf die Zacharias-Zungenstimmen eingegangen
* http://www.friedenskirche-eckenhaid.de/media/CD-Downloads/Friedenspiel_pour_le_temps.mp3, gesehen am 20.3.2018
