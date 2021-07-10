---
title: "Robot grasping in dense clutter via view-based experience transfer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chia-Lien Li
- Jian-Lun Chen
- Jyh-Jone Lee

# Author notes (optional)
# author_notes:

date: "2021-05-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *2021 International Journal of Intelligent Robotics and Applications*
publication_short: In *IJIRA 2021*

abstract: To perform object grasping in dense clutter, we propose a novel algorithm for grasp detection. To obtain grasp candidates, we developed instance segmentation and view-based experience transfer as part of the algorithm. Subsequently, we established an algorithm for collision avoidance and stability analysis to determine the optimal grasp for robot grasping. The strategy for the view-based experience transfer was to first find the object view and then transfer the grasp experience onto the clutter scenario. This strategy has two advantages over existing learning-based methods for finding grasp candidates. (1) our approach can effectively exclude the influence of noise or occlusion on images and precisely detect grasps that are well aligned on each target object. (2) our approach can efficiently find out optimal grasps on each target object and has the flexibility of adjusting and redefining the grasp experience based on the type of target object. We evaluated our approach using some open-source datasets and with a real-world robot experiment, which involved a six-axis robot arm with a two-jaw parallel gripper and a Kinect V2 RGB-D camera. The experimental results show that our proposed approach can be generalized to objects with complex shape, and is able to grasp on dense clutter scenarios where different types of objects are in a bin. To demonstrate our grasping pipeline, a video is provided at https://youtu.be/gQ3SO6vtTpA.

# Summary. An optional shortened abstract.
summary: Published in 2021 International Journal of Intelligent Robotics and Applications (IJIRA 2021)

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s41315-021-00179-y'
url_code: 'https://github.com/WilliamWang303/dense-clutter-grasp'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/gQ3SO6vtTpA'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  # placement: 1
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: []
---
