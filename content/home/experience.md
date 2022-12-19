+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Computer Vision and SLAM Research Engineer"
  company = "OLA Electric"
  company_url = "https://olaelectric.com/"
  location = "Bangalore"
  date_start = "Jun 2021"
  date_end = ""
  description = """
  * Developed an end to end autonomous driving agent using cameras, GPS and IMU sensors. Ported the agent from Carla simulator to NuScenes Dataset. Converted the pytorch model to TensorRT and developed a ROS wrapper to run on real Mahindra E2O car achieving final control prediction at 25 HZ, in a zero shot paradigm.
  * Extended the Lidar based mapping and localization LeGO-LOAM SLAM for the Velodyne and Ouster lidars and ported ROS1 to ROS2 in C++. 
  * Won the silver medal in the Kaggle Image Matching Challenge 2022 by developing an Ensemble of Deep feature matching algorithm of SuperGlue and LoFTR.
  * Trained Self Supervised Depth estimation PackNet-SfM on Indian driving dataset and on Carla simulator dataset.
  """

[[experience]]
  title = "Graduate Research Assistant"
  company = "Robotics Research Center, IIITH"
  company_url = "https://robotics.iiit.ac.in/"
  location = "Hyderabad"
  date_start = "August 2018"
  date_end = "June 2021"
  description = """
  * Worked on the intersection of SLAM, Computer Vision, Deep Learning, and Robotics. Developed robust pose graph constraints using scene semantics and developed rotation invariant deep feature descriptors for feature matching.
  * Published in ICRA and IROS conferences.
  """
  
+++
