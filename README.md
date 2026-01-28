# Thanos_wrapper
A vulkan wrapper that allows games that require ray tracing to run on older gpu's that don't have native support
Unfortunately i've had no luck brightening up the shadowed areas. You'll have to use reShade until I can figure it out or someone else can help me out with the issue.

to install, you gotta copy "vulkan-1.dll" from your c:\windows\system32 folder to your game's exe folder, then rename it to "vulkan-1_real.dll", Then unzip the wrapper to the game folder as well. Run the game, but don't expect it to run the first time, especially if you have a low amount of vram (was tested with Indiana Jones and the great circle on a GTX 1050ti)


  apparently there's a glitch where the gtx 1660 super and potentially the 1660 and ti and rtx gpu's do not work. Due to then have partial ray tracing support the wrapper fails to properly work on those devices. (although It linux does allow ray tracing on them in much the same way as AMD GPU's do.) I have a version that should work on those devices, if you have trouble with the main version try this one.
