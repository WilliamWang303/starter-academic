---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:

  - title: Research Assistant
    company: Communications and Multimedia Laboratory, CSIE Dept., National Taiwan University
    company_url: 'http://www.csie.ntu.edu.tw/~winston/'
    company_logo:
    location: Taipei, Taiwan
    date_start: '2020-07-01'
    date_end: '2021-03-31'
    description: |2-
        * Demonstrated online few-shot learning in 2020 Taiwan Innotech Expo where a robotic arm firstly picks up an unseen object in front of a camera and an object detector can be improved according to the new captured image
        * Built a novel end-to-end 6-DoF grasp detector that is twenty times faster and more accurate than previous end-to-end learning-based approaches on unseen cluttered objects
        * Achieved robotic assembly tasks by developing an algorithm that can detect 6-DoF grasps and planned a series of actions, such as grasping and re-grasping, based on the subsequent task
        
  - title: Graduate Researcher
    company: Machine and Mechatronics Design Laboratory, ME Dept., National Taiwan University
    company_url: 'http://mmd-lab.herokuapp.com/'
    company_logo:
    location: Taipei, Taiwan
    date_start: '2017-09-01'
    date_end: '2019-12-31'
    description: |2-
        * Thesis Topic: Robot Grasping in Clutter using Instance Segmentation and Representation Learning
        * Proposed a novel learning-based approach that can detect precise and accurate grasps on dense clutter scene based on noisy RGB-D image and outperformed previous end-to-end learning-based approaches on bin-picking tasks
        * Led a team of 3 people to implement the algorithm on a system consisted of the robot arm with a two-jaw parallel gripper and Kinect V2
        * Collaborated with LNC Technology, an automation company in Taiwan, for demonstrating random bin picking at 2019 Taiwan Automation Intelligence and Robot Show

  - title: Intern
    company: Department of Intelligent Machinery & Robot, Industrial Technology Research Institute (ITRI)
    company_url: 'https://www.itri.org.tw/english/index.aspx'
    company_logo:
    location: Hsinchu, Taiwan
    date_start: '2018-06-01'
    date_end: '2018-09-30'
    description: |2-
        * Designed an image processing algorithm that can detect black and white stones on the chessboard
        * Helped robot play five-in-a-row with human by adopting minimax algorithm and alpha-beta pruning

  - title: Undergraduate Researcher
    company: Bio-inspired Robotics Laboratory, ME Dept., National Taiwan University
    company_url: 'http://biorola.me.ntu.edu.tw/'
    company_logo:
    location: Taipei, Taiwan
    date_start: '2016-01-01'
    date_end: '2017-08-31'
    description: |2-
        * Led a team of 4 people to model the dung-rolling behavior of dung beetle and developed corresponding dung beetle robot that can reliably roll a ball
        * Designed trajectories and gait of each leg by observing how dung beetles synchronize their legs during the dung-rolling motion
        * Optimized the execution time of inchworm robot for wall-climbing and enhanced the speed of the movement by 60%

  - title: Intern
    company: Department of Optical Mechanism, Test Research, Inc. (TRI)
    company_url: 'https://www.tri.com.tw/en/index.html'
    company_logo:
    location: Taipei, Taiwan
    date_start: '2016-07-01'
    date_end: '2016-08-31'
    description: |2-
        * Developed a pick-and-place system that can help robot arm place chips onto different plates after AOI machine defined the chips as either normal or defective ones
        * Designed a system consisted of robotic arm and CCD that can detect defects on laptop

design:
  columns: '1'
---
