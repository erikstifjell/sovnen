# SOVNEN - for bass flute and electronics
repository for the music piece "Søvnen - for bass flute and electronics" by Erik Stifjell

# score
Søvnen, Score_square2 - Full Score.pdf should be printed on A3 (or equivalent), and cut to a square format (297mm x 297mm for A3).

# software
"søvnen" uses sovnenpatch.pd for performing the piece. It requires PureData Vanilla to run, which can be downloaded from www.puredata.info
The software can be controlled by computer keyboard ('S' and '1' - '0'), or a MIDI controller. If the latter is used, please remove the connection between [key] and [pd keypress] under 'Keypress'. Also change the number in [ctlin 80] to fit the MIDI controller being used. If you do not know the controller number, you can remove the number (leaving only ctln) and any controller number should work.

# hardware
The 3D-printed speaker fit AuraSound NS2-326-8AT Whisper 2" Extended Range Speaker Driver 8 Ohm (https://www.soundimports.eu/en/aurasound-ns2-326-8at.html). You also need a mini-jack female socket, some electrical wire and 4 wood screws (35x3,5mm).

How to build (See photos):

1: Print out Fotfeste.stl Open_Back_14mai.stl and Speaker_cup15mai.stl on a 3D-printer. 
2: Glue Fotfeste.stl to Speaker_cup15mai.stl with super glue.
3: Solder wire between speaker terminals and mini-jack female socket.
4: Place speaker into Speaker_cup15mai.stl.
5: Fasten mini-jack female socket to Open_Back_14mai.stl
6: Use wood screws to attach Open_Back_14mai.stl to the bottom part
