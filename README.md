# dirt-rally-pace-notes

This repository collects transcriptions of DiRT Rally [2.0] pace notes, contributions welcome - [see below](#contribute).  

The pace note *system* can help rally beginners to better understand the co-driver calls. The pace note *transcriptions* enable co-op playing where one player drives the car and the other acts as the co-driver reading the notes: https://www.youtube.com/watch?v=BRZHE8-c-_c 

The goal is to provide the game's pace notes as accurately as possible in a concise notation that people can read quickly and adapt to their needs or translate. In order to read the pace notes you should first take a look at the notation system below. 

This project started after the release of the original DiRT Rally. It has been updated for DiRT Rally 2.0. 
> This is how the differences in DR2 are given.

## Understanding pace notes
You should read this [blog entry](http://blog.codemasters.com/dirt/04/co-driver-calls-explained/) by the guy that reads the pace notes for the original DiRT Rally.

## System

There doesn't seem to be an official notation, so [this one](http://www.automobilemag.com/news/a-beginners-guide-to-rally-pace-notes/) mostly inspired the following (simplified) notation.

### Corners
In ascending severity: ``x6, x5, x4, x3, x2, x1, SQx, HPx, ACx`` where ``x`` is either ``l`` or ``r``.  
> In DR2 the numbers shifted, e.g. l5 would now be 6l: `flat, 6x, 5x, 4x, 3x, 2x, 1x, sqX, open-hpX, hpX`. To cover the same spectrum, a previous 6 is now called flat, and acute corners become hairpins.

Corners can be ``long`` or ``hlong`` (half long).  
> DR2 corners can be `short`, `long`, `verylong`, `extralong`, or `extraextralong`.

They can tighten to a higher severity, ``>``, or open to a lesser one, ``<``. 
> In DR2 it is also called if the road `opens` or `tightens` through a corner.

### Road geometry
The road can be ``open`` or ``tight``, form ``dent``s or (``long``) ``cr``ests.  
The latter are often followed by a ``jmp`` (jump), which might only happen at certain speeds: ``jmp?``.  
Crests/jumps can be particularly ``small`` or ``big``.  
Bad ``camber`` means a section or corner should be passed with care and perhaps less speed.  
``bmp`` denotes bumpy sections.  

### Road boundaries
``gate``s, ``post``s, ``tunnel``s, ``bridge``s require the driver to stay off the edge of the road.   
``rock``s, ``log``s, ``ditch``es, ``bank``s can be placed on the inside, outside, or exit of a corner: ``-in, -out, -exit``. This is often combined with a placement call.

### Change in road characteristics
The next section can go ``[up]`` or ``[down]``, it ``[opens]`` and ``[narrows]``.  
It can be covered by ``[ice]``.

### Car placement
Drivers can be advised to stay in the middle of the road or left or right of the middle: ``keepm, keepl, keepr``.  
In corners, calls are made to ``keepin`` or even ``cut`` the corner.  
``dontcut`` means to stay clear of the inside, ``keepout`` advises an outside line through a corner.  
``line`` means taking a sequence of one or more corners straight. 

### Orientation
``Junc``tion, ``turn``, and ``cross``roads denote segments where the driver must take care not to take the wrong way.  

### Note succession
``/`` (over, past, for, through) connects different characteristics that occur simultaneously.  
Quick successions of stage characteristics are indicated by simple enumerations in a single line.  
Otherwise, a number is used representing distance between characteristics in meters: ``60, 80, 100, 130, 150, 200, 300, 400``

### Driver attention
Caution is advised by ``!``.  
This can be combined with advice of ``slowing`` or ``braking``.  
``deceptive`` warns the driver, e.g. not to succumb to a wrong way.  
``finish`` ends the stage and pace notes.  

## Contribute
Feel free to submit your own transcriptions, following the requirements below:
- record or find the replay of a single stage in DiRT Rally [2.0] from the *head, dash, or chase* camera using the *English speaking* co-driver 
- write down the *complete* pace notes using the notation above in a text file, e.g. `Dirt-Rally-Monaco-Route-de-Turini.txt`
- if needed, upload the replay and make it accessible (e.g. on YouTube)
- send the text file along with the replay link to soong.construction.dev+gh@gmail.com

Some further hints:
- if needed, you can extend the system (but name & describe the extensions in the mail you send)
- when transcribing from a video platform like YouTube, lowering the video playback speed can be a big help
- fast "world record" runs through a stage make it particularly hard to get all the co-driver calls
- try and use replays with a proper flow, i.e. no crashes or resets of the car
