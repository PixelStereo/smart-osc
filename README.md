# smart-osc
Modul8 OSC module with user-friendly adresses and timed actions

### QuickStart
This module rewrite Modul8 keyword as hierarchical OSC addresses. It uses dot as an instance separator for layers.

##### layers
The keyword /md8key/ctrl_layer_alpha/1 is accessible with the following OSC address :

    /layer.1/alpha

##### master
The keyword /md8key/ctrl_master_scale/0 is accessible with the following OSC address :

    /master/scale

##### Animations
Modul8 does not support animations out-of-the-box. Smart OSC does.
If you want to have a nice fadein in 3 seconds, just send the following OSC message :    

    /layer.1/alpha 1 3000

### Issues
If you found a bug or want to add a feature-request, please check that it has not already be discussed or planned. Then create a new issue.

### Credits
Smart OSC is produced and developed by @PixelStereo

### Licence
Smart OSC is licenced under the GPL v3 licence.
