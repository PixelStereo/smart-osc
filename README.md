# smart-osc
Modul8 OSC module with user-friendly adresses and timed actions

### QuickStart
This module rewrite Modul8 keyword as hierarchical OSC addresses. It uses dot as an instance separator for layers.
##### layers
* /md8key/ctrl_layer_alpha/1 => /layer.1/alpha 
##### master
* /md8key/ctrl_master_scale/0 => /master/scale

If you want to have a nice fadein in 3 seconds, just send the following commands : 
/layer.1/alpha 1 3000

### Issues
If you found a bug or want to add a feature-request, please check that it has not already be discussed or planned. Then create a new issue.

### Credits
Smart OSC is produced and developed by @PixelStereo

### Licence
Smart OSC is licenced under the GPL v3 licence.