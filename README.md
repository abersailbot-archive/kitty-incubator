Kitty-incubator
===============

Incubation for kitty ideas and plans

Electronics rail clip
---------------------

Rails for the electronics box to clip onto.

  - Use fir tree clips

    ![clip](https://raw.githubusercontent.com/abersailbot/kitty-incubator/master/fir_tree_clip.jpg)

  - Two rails
  - Rails made from aluminum

Power switch
---------------------

Have a cool looking toggle switch with an LED on it.

Stick it on the outside of the electronics box.

Vision system
-------------

Vision for guiding through the navigational accuracy task.

### Algorithm

  - Hybrid system
  - Camera used to guide between the buoys
  - Navigate using weighted average between input from vision and GPS waypoints
    - weight based on the certainty of buoy positions
  - Do circle detection on orange looking objects
  - Move the boat to try to keep both circles at equal distances from the
    center of the field of view

### Camera

  - Standard inexpensive webcam or Pi cam
  - Fit inside a go-pro style case on deck
  - Put a fish-eye style lens on
    - can get one made to work with iPhones
