# Japanese Chords Glove

## Introduction

The idea of this project is to create a very basic musical instrument that can be played using a glove that one wears over the hand. Because I'm right-handed, I'll be making the glov for my left hand and playing with my right.

This is an exploration of chord progressions. My knowledge of music theory is very basic, so this project is also a vehicle to learn more about the technical details of musical chords and audio synthesis using Processing.

## Defining Terms

This project relies on some concepts of music theory that were important for me to learn about and understand.

### What is a "Japanese chord progression"?

This project was born after I saw a YouTube video about common chord progressions in modern Japanese classical and anime music.

See [[Sakamoto, Hisaishi, et. al.] - Common Japanese Chord Progressions](https://youtu.be/yKV58VVGV9k) on YouTube.

The four chords in much of the Japanese music discussed in the video are (illustrated here in root, 1st, and 2nd inversions to span two octaves and to make my instrument more flexible/expressive):

### Root

| Chord Number | Chord in C-Major | Root Chords | Frequencies in Hz         |
| ------------ | ---------------- | ----------- | ------------------------- |
| III          | E                | E3, G#3, B3 | 164.859, 207.727, 247.030 |
| IV           | F                | F3, A3, C4  | 174.674, 220.000, 262.686 |
| V            | G                | G3, B3, D4  | 196.065, 247.030, 293.724 |
| VI           | A                | A3, C#4, E4 | 220.000, 277.262, 329.724 |

### 1st Inversion Chords

| Chord Number | Chord in C-Major | 1st Inversion | Frequencies in Hz         |
| ------------ | ---------------- | ------------- | ------------------------- |
| III          | E                | G#3, B3, E4   | 207.727, 247.030, 329.724 |
| IV           | F                | A3, C4, F4    | 220.0, 261.686, 349.309   |
| V            | G                | B3, D4, G4    | 247.030, 293.724, 392.089 |
| VI           | A                | C#4, E4, A4   | 277.262, 329.724, 440.0   |

### 2nd Inversion Chords

| Chord Number | Chord in C-Major | 2nd Inversion | Frequencies in Hz      |
| ------------ | ---------------- | ------------- | ---------------------- |
| III          | E                | B3, E4, G#4   | 246.94, 329.63, 415.3  |
| IV           | F                | C4, F4, A4    | 261.63, 329.63, 440.0  |
| V            | G                | D4, G4, B4    | 293.67, 392.00, 493.88 |
| VI           | A                | E4, A4, C#5   | 329.63, 440.0, 554.37  |

### Some examples of these chord progressions used in Japanese music

Joe Hisaishi - One Summer's Day

https://www.youtube.com/watch?v=smn0HOvwoZ8

Ryuichi Sakamoto - Merry Christmas Mr. Lawrence

https://www.youtube.com/watch?v=hDaQF-LNrug

## Inspirations

This project is inspired by my current exploration of several topics, including ***enactment*** and ***embodiment*** in the field cognitive science. Enactment and embodiment are topics that originated in the 1990s in cognitive science. They arose from a desire to move beyond ***cognitivist*** models of human cognition where thought is defined as a form computation and our brains are basically meat computers. Cognitivism originated in the 1950s and sadly influences a lot of thought today. Embodiment proposes that our mind may be larger than our brain and that our minds are not at all like computers, because unlike computers, our minds engage in ***[autopoiesis](https://en.wikipedia.org/wiki/Autopoiesis)***, or self organization and self-maintenance, to maintain homeostasis.

The COVID-19 pandemic has made me accutely aware of being so dependent on traditional digital interfaces, like screens, reinforces the mind-body split. I find myself always trying to get "out of my head." In combatting this, I've developed habits of going outside, walking on grass barefoot, playing piano, petting my dog, meditating, and generally trying to have more embodied experiences.

Making a musical instrument I could play with my hand, or turning my hand into a musical instrument is an extension of these explorations.

## Equipment Used

- A [Makey Makey](https://makeymakey.com/) Kit
- An old leather gardener's glove.
- [Cardboard for prototyping](https://www.amazon.com/Corrugated-Cardboard-Sheets-24-Pack-Inserts/dp/B079QY6MMX/ref=sr_1_1?dchild=1&keywords=juvale+8.5+11+cardboard&qid=1606510018&sr=8-1)
- [Copper tape](https://www.amazon.com/Zehhe-Copper-Foil-Double-Sided-Conductive/dp/B01MR5DSCM).

## Software Used

- [Processing](https://processing.org/)
- [Minim](https://github.com/ddf/Minim): A Processing library for sound

## Images

### User Interface

The user interface of my project is very simple. Indeed it isn't really a user interface, but rather it is a visualization of what is happening on the hardware. In that sense it is a way of offering ***non-auditory visual feedback*** to the user.

![User Interface](images/UI.gif)

The interface has 5 buttons, one for each finger.

### Hardware



### The software/hardware in action.

![chord-glove](images/chord-glove.gif)

[See original video with sound on Vimeo](https://vimeo.com/484577141).

### 

## What I learned and next steps



## External Resources and Studies

Images of notes with corresponding frequencies:

![piano-scale-hertz-frequency-notes](images/piano-scale-hertz-frequency-notes.png)

([Source](https://novaspire.wordpress.com/2016/01/18/understanding-the-frequency-spectrum-the-art-of-mixing-video/piano-scale-hertz-frequency-notes/))

Image of Notes with Corresponding Frequencies:

![notes](images/notes.GIF)

([Source](https://newt.phys.unsw.edu.au/jw/notes.html))

8notes.com Piano Chord Chart

https://www.8notes.com/piano_chord_chart/f.asp

## Acknowledgements

Keyboard Piano by Neel Virdy

https://www.openprocessing.org/sketch/99584/#

University of New South Wales: Note names, MIDI numbers and Frequencies

https://newt.phys.unsw.edu.au/jw/notes.html

