#gazebo_plugins

##Collection of small gazebo plugins
 
###MimicJointPlugin

A simple (Model) plugin for Gazebo in order to add to Gazebo the mimic joint functionality that exists in URDF (ROS). Inspired by code of Goncalo Cabrita.

  - *XML Parameters*

    - joint (Required)

      A **string** specifying the name of the joint to be mimic-ed.

    - mimicJoint (Required)

      A **string** specifying the name of the mimic joint.

    - multiplier

      A **double** specifying the multiplier parameter of the mimic joint.

    - offset

      A **double** specifying the offset parameter of the mimic joint.


###Hoping to add more plugins....

Notes
------

If there is a need, please make an issue and I'll see what I can do to add that functionality/plugin.

License
----

BSD


Copyright (c) 2014, **Konstantinos Chatzilygeroudis**
