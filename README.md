# dirt-rally-pace-notes

This collects transcriptions of DiRT Rally pace notes, contributions welcome. These notes enable co-op playing where one player drives the car and the other acts as co-driver reading the notes.

Now that DiRT Rally 2.0 has long since been released, I'll try and update the system and pace notes.
> This is how the differences in DR2 are given.

My goal is to provide the game's pace notes as accurately as possible (given the manual process of writing the notes from replays) in a concise notation that people can read quickly and adapt to their needs or translate. 

## Understanding pace notes
You should read this [blog entry](http://blog.codemasters.com/dirt/04/co-driver-calls-explained/) by the guy that reads the pace notes in the game.

## System
There doesn't seem to be an official notation, but [this one](http://www.automobilemag.com/news/a-beginners-guide-to-rally-pace-notes/) looks thorough to me and can be used to understand the following (simplified) notation.

### Corners
In ascending severity: ``x6, x5, x4, x3, x2, x1, SQx, HPx, ACx`` where ``x`` is either ``l`` or ``r``.  
> In DR2 the numbers shifted, e.g. l5 would now be 6l: `flat, 6x, 5x, 4x, 3x, 2x, 1x, sqX, open-hpX, hpX`. To cover the same spectrum, a previous 6 is now called flat, and acute corners become hairpins.

Corners can be ``long`` or ``hlong`` (half long), some are `immediate`.  
> DR2 corners can be `short`, `long`, `verylong`, `extralong`, or `extraextralong`. Many are `unseen`, some `sudden`.

They can tighten to a higher severity, ``>``, or open to a lesser one, ``<``. 
> In DR2 it is also called if the road `opens` or `tightens` through a corner.    
> DR2 will call out if a corner benefits from an `early` or `late` turn-in/apex, or if it `continues` past a given way point.

### Road geometry
The road can be ``open`` or ``tight``, form ``dent``s or (``long``) ``cr``ests.  
> DR2 calls out `dip`s instead of dents.  

Crests are often followed by a ``jmp`` (jump), which might only happen at certain speeds: ``jmp?``.  
Crests/jumps can be particularly ``small`` or ``big``.  
Bad ``camber`` means a section or corner that requires a certain line and perhaps less speed.  
``bmp`` denotes bumpy sections.  

### Car placement
Drivers can be advised to stay in the middle of the road or left or right of the middle: ``keepm, keepl, keepr``.  
In corners, calls are made to ``keepin`` or even ``cut`` the corner.  
``dontcut`` means to stay clear of the inside, ``keepout`` advises an outside line through a corner.  
``line`` means taking a sequence of one or more corners straight. 

### Road boundaries
``gate``s, ``post``s, ``tunnel``s, ``bridge``s require the driver to stay off the edge of the road.   
``rock``s, ``log``s, ``ditch``es, ``bank``s can be placed on the inside, outside, or exit of a corner: ``-in, -out, -exit``. This is often combined with a placement call.  
(Tight) `chicane`s ask for a specific speed and car placement, depending on a `-left` or `-right` entry.  
`layby`s can offer more space to one side of the road, but might also mean less space due to parked cars.   
`bale`s are used to artificially tighten a corner.

### Change in road characteristics
The next section can go ``[up]`` or ``[down]``(hill), it ``[opens]`` and ``[narrows]``.  
A `[water]` splash might require to switch on the windscreen wipers, while `[grid]`s can jerk the steering wheel.  
The road can be covered by ``[ice]`` patches. For longer sections, calls are made when `[ice]-starts` or `-clears`.  
> DR2 distinguishes `[snow]` from ice. It also calls out the transition to `[gravel]`, `[tarmac]`, and `[cobble]`.  

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
> In DR2, the pace notes continue until the driver is to `stop`.


