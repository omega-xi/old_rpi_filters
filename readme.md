Basic Scanline and aperture effects by nimitz@shmupsforum
I used the source of the ScanLineTV filter by "Forgotten" as a base, so giving credit to the original author.
(even though very little of the original code is left at this point)

The plugins were designed for VBAm, they also are compatible with KEGA or any other software 
that support .rpi pixel filters/plugins.

Quite a few variations are included, I would recommend finding which work best for you and deleting the others.

The filers are split into three groups:
	-ScanlinesXX (fat scanlines)
		this is your basic 2x scanlines filter with half the lines being darker.
	-ThinScanlinesXX (thin scanlines)
		basic 4x scanlines filter (often just ends up making the overall picture darker).
	-14scanlinesXX (1/4 scanlines)
		only one line out of four is darker.
	-GrilleXX (aperture grille)
		same idea as 14scanlines but on both axes, mimicking an aperture grille.
	-DotsXX
		the aperture grille without horizontal "scanlines"
	-MeshXX
		Somewhat experimental pattern, much less of a "pixel crawling" effect than conventional "shadow mask" type filters
	
The XX number is the scanline "transparency", the higher the less visible they will be. I usually find 60 to be much
too dark so I didn't include anything under 60.
