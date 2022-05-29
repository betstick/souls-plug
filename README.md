# souls-plug
Dark Souls Asset Importer for Blender

# Alpha quality character importer for DSPTDE (DSR might work)
Lets you import full meshes with bones and textures ready for rendering in Eevee. Cycles might be supported, but Cycles doesn't support Specular stuff as well, and this tool is primarily for modding as opposed to rendering.

Most things are importing without issue. Some odds and ends are missing textures. There's still random "crash" events and other unreliable behavior.

# TODO (in order of realism/priority)
add mesh exporting support.

add animation importing support. its in the works.

add material export support.

get the code licensing in order.

clean up the code. its terrible.

improve performance. its also terrible.

add animation exporting support. this may not be possible.

switch off C# to C++ once possible.

# How to use:
You need to have Blender 2.93 LTS set up. I will only support the latest LTS releases for now.

Install the souls-but-hole.zip file into Blender as an addon. Make sure to configure the settings to point to the correct locations.

Compile souls-tongue from source.

Make sure you can see the Blender System Console (the CMD on Windows). Lots of useful feedback and info.

Somewhere hidden in Blender is a SoulsPlug menu, punch in the character ID, and hit "Import". If you're lucky, you'll get a pretty model.

# Credits (people who's code i stole)
YAVNE Blender addon from fedackb (used for getting the vertex normals just right)
blender-flver Blender addon from elizagamedev (needed the skeleton code)
SoulsFormats from JKAnderson
DSAS from Meowmaritus (will be used for animation support once I get around to it)
if your name isn't on the list but should be, let me know. will eventually get into full license compliance.
