# KlinterAI

## Purpose

It would be easier to involve a new technique to study on the work within the construction site where contractors work in the field, plant, and operate machines. It is necessary to understand the stages of development of a construction site such that a daily report can be generated from it. This improves the productivity of the foreman and managers at the site by involving a scheduling and monitoring application. 

## Ideation

### Work Context Diagram

![image](https://user-images.githubusercontent.com/1046939/199220830-a0404cac-b470-4307-9f03-09e3a79b7039.png)

The work context diagram involves these steps:

(1) The positions of people and machinery are recorded first. 
(2) The activity is recognized based on the video output
(3) Scheduled Walks assisted by a camera are planned on a routine basis
(4) The number of piles, site conditions and hazards are recorded into the daily report
(5) A timeline based scheduling app shows the activities tracked within a schedule

## Methodology

![image](https://user-images.githubusercontent.com/1046939/199221660-662b68e5-52be-4b81-b4c3-dbeacb0c203e.png)

In the methodology section, the AI software detects objects and recognizes the activity to be saved to an external database. 

(1) Object Detection
(2) Activity recognition
(3) Construction Scheduling

## Dataset

The dataset consists of Construction Site Images (more than 14k), whose annotations are recorded using [CVAT.ai](http://CVAT.ai). The activities are written against these annotated images to create the ground truth for activity recognition. 

## Metric Visualization

![image](https://user-images.githubusercontent.com/1046939/199222111-277f9df0-a35f-4a07-ba37-cafde66c9ad7.png)

The figure given above, shows the annotation workflow, and the metrics involved in:

(1) Separating signals into activities
(2) Recognizing the activities from those clustered activities based on the timeline

## Steps to be Taken while annotating

The work must always refer to Underground, Ground, constructed area and Scaffolding and other structures such that a meaningful table with a number of activities are shown as an activity map. 

•	Work involved in the Underground

•	Work involved in the Ground

•	Work involved in a constructed area

•	Work involved in Scaffolding

While annotation, each activity must be tagged wherever possible with electricity, oil consumtpion or material used during the activity. 

•	Tag each activity as electricity or oil consumption for usage and the material name for usage
