+++
author = ""
description = "Pair of fully autonomous underwater robots which placed third internationally in RoboSub 2016"
title = "Thor and Loki"
date = "2018-08-15T22:43:35+00:00"

thumb = "thor_loki_thumb.png"

type = "project"
robot_type = "Pair of Mobile Underwater Robots"
application = "International RoboSub 2016 Competition Entry (Won 3rd place)"

org_name = "Cornell University Autonomous Underwater Vehicle Team"
org_link = "http://cuauv.org"
org_github = "https://github.com/cuauv/software"

role = "Software Team Member"
timeframe = "September 2015 – July 2016"

[[videos]]
title = "Competition Video"
width = 800
height = 400
src = "https://www.youtube.com/embed/KB5b_M7Ps2Y"

[[videos]]
title = "Torpedoes Task Video"
width = 800
height = 400
src = "https://www.youtube.com/embed/GOj6JVd1Q9E"

[[images]]
src = "thor_crane_below_resize.jpg"
caption = "Thor being lifted into the competition pool by the crane."

[[images]]
src = "torpedoes_vision_gui.png"
caption = "Visualization of the torpedoes task algorithm executing in real-time."

[[images]]
src = "thor_debug_resize.png"
caption = "Thor being debugged via the shared memory editor and plotter."

[[images]]
src = "thor_bins_sim_resize.png"
caption = "Thor testing mission logic inside of the custom simulator."

[[images]]
src = "thor_sim_resize.png"
caption = "Thor exploring the simulator."

+++
CUAUV was my first experience working on a relatively complex
robotics project, an underwater robot with a 50-person team
consisting of about 15 software team members. (I had competed in high
school robotics, but I was leading a relatively small 3-person team.)
The objective of CUAUV is 
to produce a robot to compete in the international RoboSub
competition. As a team member, I developed an interest
in computer vision, researching topics such as graph-based image
segmentation to enable object detection invariant to lighting
conditions and visual egomotion in order to caculate velocity without
an expensive sonar sensor. I implemented simple proof-of-concept prototype
algorithms for both of these. 

As the competition takes in July, some team members opt to stay
on-campus over the summer to work on the robot. I opted to stay
during Summer 2016 as a sophomre. I worked extensively on computer vision algorithms
and high-level state machine and control logic to
to complete the "Torpedoes" task at RoboSub 2016. The task consisted of
identifing targets labeled with letters, removing a physical cover from a target, 
and shooting plastic projectiles at targets with specified letters.
(Video and images are shown below.) I spent nearly all of my time
that summer writing computer vision code, testing and collecting logs in the pool,
and revising and re-desgining code as needed to account for new failure
modes, re-running against the collected log data, and finally
re-testing in the pool.

I had a fantastic experience attending RoboSub 2016, speaking with
other teams about how they had approached the challenges and watching
my code manuver the vehicle around the obstacle course. I was super
excited when our team acheived third place.
