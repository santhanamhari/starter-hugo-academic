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
  - title: Graduate Research Assistant 
    company: Shi Research Group
    company_url: ''
    company_logo: 
    location: Philadelphia, PA
    date_start: '2021-09-01'
    date_end: ''
    description: |2- 
        * Projecting 3D mesh models into 2D images, and using SOLO v2 to learn relevant information about image's edge contours for 3D reconstruction.
        * Adding additional branches to SOLO v2 architecture in order to predict the 3D flow field along each contour, as well as end points of each contour. 
        
  - title: Advanced Robotics R&D Intern
    company: Amazon Robotics
    company_url: ''
    company_logo: 
    location: Boston, MA
    date_start: '2021-06-01'
    date_end: '2021-08-31'
    description: |2-
        * Trained Mask R-CNN architecture on one setting's sensor data and tested on second sensor's data, in order to establish baseline result. 
        * Created augmented data by copying foreground objects, based on derived position, rotation, and scale distribution, into second setting with no background.
        * Developed GAN model to create realistic blending after foreground placement.
        * Used augmented data plus orginal data to train Mask R-CNN model and achieved improvement in average precision and recall.

  - title: Undergraduate Research Assistant
    company: Princeton Senior Thesis
    company_url: ''
    company_logo: 
    location: Boston, MA
    date_start: '2019-09-01'
    date_end: '2020-05-31'
    description: |2-
        * Inverted a pre-trained Mask R-CNN architecture to reverse engineer input training video sequences from just output binary masks.
        * Optimized noise as input tensor and added novel weighted batch normalization loss and pixel variance loss to existing Mask R-CNN architecture.


  - title: Research Intern
    company: Princeton Project X
    company_url: ''
    company_logo: 
    location: Boston, MA
    date_start: '2019-06-01'
    date_end: '2019-08-31'
    description: |2-
        * Combined ConvLSTM with PReMVOS, a semi-supervised segmentation network that tracks an object based on video's first frame.
        * Adapted network to track object in video based on template image, rather than video's first frame, and achieved promising J&F mean scores.

  - title: Engineering Intern
    company: Lightening Energy
    company_url: ''
    company_logo: 
    location: Dover, NJ
    date_start: '2018-06-01'
    date_end: '2018-08-31'
    description: |2-
        * Developed and designed a prototype for a battery pack configuration that electrically powers an industrial device. 
        * Programmed a battery management system (BMS) and power supply to work in cohesion with the pack for factory settings. 
  
  - title: Summer Intern
    company: Princeton Plasma Physics Laboratory (PPPL)
    company_url: ''
    company_logo: 
    location: Princeton, NJ
    date_start: '2017-06-01'
    date_end: '2017-08-31'
    description: |2-
        * Detected oscillations using Langmuir probes by altering the magnetic field strength and probe voltage within cylindrical plasma tube.
        * Discovered ion acoustic waves caused detected oscillations using MatLab and co-wrote a paper featured on the official PPPL website. 
design:
  columns: '2'
---
