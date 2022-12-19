---
title: Tutorial on pose graph optimization using g2o 
summary: Example of Pose Graph SLAM and landmark based SLAM using syntheic dataset 
tags:
- SLAM
- Robotics
# date: "2019-05-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Comparison of Robot poses before and after optimization
  focal_point: Smart

url_code: "https://github.com/UditSinghParihar/g2o_tutorial"
url_pdf: ""
url_slides: "https://www.notion.so/G2O-General-Graph-Optimization-Framework-151b8c5f93bb4519be9fd5c2f9bfa112"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---


1. This repository is the tutorial on the general edge types(EDGE_SE2 and EDGE_SE3) and vertex types(VERTEX_SE2 & VERTEX_SE3) found in [g2o](https://github.com/RainerKuemmerle/g2o), using python. The accompanied documentation on results can be found in the [notion page](https://www.notion.so/G2O-General-Graph-Optimization-Framework-151b8c5f93bb4519be9fd5c2f9bfa112).  
2. We have covered two common scenarios found in SLAM: Pose Graph SLAM and Landmark based SLAM using synthetic dataset. The main goal is to cover how to formulate a graph based optimization problem in proper g2o format, using g2o's vertices, edges and information matrix.  
3. Problem statement:  
	1. Pose Graph SLAM: A robot is travelling in a oval trajectory. It is equipped with wheel odometry for odometry information and RGBD sensors for loop closure and ICP transformation. Due to noise in wheel odometry it generated a noisy estimate of the trajectory. Our task is to use loop closure pairs to correct the drift.  
	![Alt Text](lc_pose_graph.png)  
	2. Landmark SLAM: A robot observes a cube from five different locations. The robot is equipped with RGBD sensors and would be using those to calculate odometry and the map of the cube. Due to noise in the sensors, it obtained a erroneous estimate of its poses and vertices of the cube. Our task is to couple odometry measurements and cube's vertices(landmarks) measurements to generate a consistent and better estimate of those values.  
	![Alt Text](g2o_landmark.png)  