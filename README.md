# dirt-rally-pace-notes

This collects transcriptions of DiRT Rally pace notes, contributions welcome. These notes enable co-op playing where one player drives the car and the other acts as co-driver reading the notes.

My goal is to provide the game's pace notes as accurately as possible (given the manual process of writing the notes from replays) in a concise notation that people can read quickly and adapt to their needs or translate. 

## Understanding pace notes
You should read this [blog entry](http://blog.codemasters.com/dirt/04/co-driver-calls-explained/) by the guy that reads the pace notes in the game.

## System

There doesn't seem to be an official notation, but [this one](http://www.automobilemag.com/news/a-beginners-guide-to-rally-pace-notes/) looks thorough to me and can be used to understand the following (simplified) notation.

### Corners
In ascending severity: ``x6, x5, x4, x3, x2, x1, squarex, hpx, acutex`` where ``x`` is either ``l`` or ``r``.  
Corners can be ``long`` or ``hlong`` (half long).  
They can tighten to a higher severity, ``>``, or open to a lesser one, ``<``.

### Road geometry
The road can be ``open`` or ``tight``, form ``dent``s or (``long``) ``cr``ests.  
The latter are often followed by a ``jmp`` (jump), which might only happen at certain speeds: ``jmp?``.  
Bad ``camber`` means a section or corner should be passed with care and perhaps less speed.  
``bmp`` denotes bumpy sections.  

### Road boundaries
``gate``s, ``post``s, ``tunnel``s require the driver to stay off the edge of the road.   
``rock``s, ``log``s can be placed on the inside or outside of a corner: ``-in, -out``. This is often combined with a placement call.

### Change in road characteristics
The next section can go ``[up]`` or ``[down]``.  
It can be covered by ``[ice]``.

### Car placement
Drivers can be advised to stay in the middle of the road or left or right of the middle: ``keepm, keepl, keepr``.  
In corners, calls are made to ``keepin`` or even ``cut`` the corner.  
``dontcut`` means to stay clear of the inside.  

### Orientation
``Junc``(tion) and ``turn`` denote segments where the driver must take care not to take the wrong way.  

### Note succession
``/`` (over/for/through) connects different characteristics that occur simultaneously.  
Quick successions of stage characteristics are denoted as either ``:`` (immediate) or ``->`` (into).  
Otherwise, a number is used representing distance in meters: ``60, 80, 100, 130, 150, 200``

### Driver attention
Caution is advised by ``!``.  
This can be combined with advice of ``slowing`` or ``braking``.  
``deceptive`` warns the driver, e.g. not to succumb to a wrong way.  
``finish`` ends the stage and pace notes.  



