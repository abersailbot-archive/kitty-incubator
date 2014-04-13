Kitty-incubator
===============

Incubation for kitty ideas and plans

Sailing Algorithm
-----------------

Sail down lines, rather than between waypoints.

  - Implement using numpy vectors
    - numpy is 'free' - preinstalled on target device
  - Use a bunch of simple layers of vectors
    - just add them together

  - vector layers for each point `(i, j)`:
    - unit vector pointing to the nearest point on the nearest line
      - multiplied by a factor of the distance from the line

    - unit vector pointing in the same direction as the nearest line


Electronics rail clip
---------------------

Rails for the electronics box to clip onto.

  - Use pipe clips

    ![clip](https://raw.githubusercontent.com/abersailbot/kitty-incubator/master/fir_tree_clip.jpg)

  - Two rails
  - Rails made from aluminum
  - Use 15mm clips, 10mm aluminum
  - Add felt padding to the upper half of the clip

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
