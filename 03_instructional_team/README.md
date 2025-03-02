# Instructional Team Playbook

## How do you interact with the repo?
The Technical Facilitator will deliver the content in the `/01_materials/slides` directory. You are encouraged to live code with participants during live sessions. Please ensure that live coding files are uploaded to a new directory called `/live_code` under `/04_this_cohort` in this repository using a new branch. Please open a pull request for it to be merged.

## How does the module flow?
The module is organized into 3 main directories:
1. Slides
2. Assignments
3. Homework

The `/01_materials/slides` directory contains the live learning session slides.

The `/02_assignments` contains assignments participants should submit for evaluation as  `complete` or `incomplete`. The assignments measure a participant's achievement of the learning outcomes, and help technical facilitators determine if a participant has successfully completed the learning module. 

The `/03_homework` directory contains homework participants can complete to further develop and practice the skills covered in a learning module. Homework is optional, but participants are encouraged to complete as much as they can. 

### Week 1

#### Live Learning Session 1
The focus of the first live learning session will be to introduce the Production module especially Machine Learning System Design.

#### Live Learning Session 2
The focus of the second live learning session is to deliver the content of Data Engineering Fundamentals. 

#### Live Learning Session 3
The focus of the third session is to teach the participants how to work with training data.

#### Assignment 1
This assignment will introduce participants to working with parquet files.

### Week 2

#### Live Learning Session 4
The fourth live learning session will introduce the participants to Feature Engineering.

#### Live Learning Session 5
The fifth live learning session will introduce the participants to model development and evaluation.

#### Live Learning Session 6
The fifth live learning session will continue exploring model development and evaluation.

#### Assignment 2
The assignment for their final week in this module is to construct a preprocessing and model pipeline to predict the variable `income`.

## How do you assign assignments?
Technical Facilitators are encouraged to introduce assignments as early as possible in the learning module. The Technical Facilitator should describe the assignment to participants and explain how the topics covered in the module will equip them with the knowledge and skills to complete the assignment. 

## How is an assignment is expected to be completed and delivered?
Participants are expected to complete the assignment by the end of the first week. They will deliver the assignment by opening a pull request on their copied repo. The participants will also add a Learning Support Staff as a reviewer indicating they delivered a completed assignment, and it is ready to be evaluated as `complete` or `incomplete`.

## What is the criteria for `complete` or `incomplete`?
The criteria for a `complete` or `incomplete` is if all parts of the program are working, and nothing in the code is broken. For some assignments, a rubric is provided outlining the criteria needed to assess an assignment as incomplete.

## How to evaluate?
If the participant's solution works, then their assignment should be assessed as `complete`! Technical Facilitators and the Learning Support Staff should focus on providing constructive feedback to participants who need to improve their code. If the solution does not work, then the assignment is `incomplete`. Facilitators should provide constructive feedback on their existing code, and guide them to get their solution working.

## How will feedback be given?
Feedback should be given through the pull request a participant has made. Technical Facilitators are encouraged to allow participants to make revisions if needed. In order to maximize learning, feedback should be constructive, and specific.

<hr>

## Definitions
**Live Learning Sessions**: A Live Learning Session is a synchronous period of time, lasting up to 2.5 hours, where the Technical Facilitator will facilitate and deliver the content and learning outcomes online through Zoom. Participants are encouraged to participate and ask questions as they learn. 10 minute breaks are encouraged once per hour.

**Work Period**: A Work Period is an asynchronous period of time, lasting up to 3 hours. Participants will work on assignments and/or homework during this block of time. Learning Support Staff are to be present online through Zoom to assist participants and answer any questions they may have. As work periods are asynchronous and flexible, participants can choose to work on their own time. However, it is encouraged that they work during the block of time when a Learning Support Staff is present.

**Assignments**: An Assignment is work assigned as part of the learning modules. They provide an opportunity for participants to integrate and synthesize what they have learned throughout the week to meet the set learning outcomes.

## generate_slides.sh

This script is designed to convert Markdown files located in a specified folder into slide presentations using Marp CLI, allowing for the generation of either HTML or PDF formats based on user input. It includes an option to apply a custom CSS theme to the slides by specifying a theme path. The script also provides a help function detailing its usage, options, and examples for convenience. It ensures the necessary directories exist, validates the presence of Marp CLI on the system, processes each Markdown file found in the specified directory, and outputs the generated slides into a designated output folder, displaying the status of each operation and a completion message. The only configuration needed is to set where the md files are and where you would like the pdf/html files to be placed.
