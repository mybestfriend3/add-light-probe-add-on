# add-light-probe-add-on
Blender 2.8 (or Blender 2.90.1 if you use version 0.4 or 0.5) add-on to add a light probe aligned with selected vertices<BR>
Intall the zip as usual<BR>

Notes for 0.4 (assuming you have been redirected here from the demo/tuto on youtube)<BR>
Select one object or more in 3Dview (eventually in edit mode), type  F3 and search for "aligned"<BR>
Choose the type(s) of probe(s) to be added (eventually just a bounding box)<BR>
Choose a number of samples of rotation around different axis (if needed) and beware brut force is used (avoid too many samples)<BR>
Select "mimic drivers" if the probe parameters are to be copied from probes named "AlignedCubeMapBase" and "AlignedIrrVolBase"<BR>
Press OK et voila
  
Notes for 0.5 (assuming you already know 0.4 since no tuto available yet and a bit of guessing is necessary)
In this version probes are parented to the bounding box, allowing modification of the bounding box without creating new probes)
Select one object or more in 3Dview (eventually in edit mode), type  F3 and search for "aligned" or use le Object or Mesh menu in 3Dview<BR>
Choose the type(s) of probe(s) to be added <BR>
Choose a number of samples of rotation around different axis (if needed) and beware brut force is used (avoid too many samples)<BR>
Select "mimic drivers" if the probe parameters are to be copied from probes named "AlignedCubeMapBase" and "AlignedIrrVolBase"<BR>
Alternatively just update the bounding box if it has already been create and press OK for the probes to be updated according to the bounding box <BR>
