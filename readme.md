Gabrielle Madden

This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
![1](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/1.png?raw=true)

## Activity 2
![2](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/2.png?raw=true)

## Activity 3
See the entire docker build log [here](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/docker-build-log.txt)

_First Part_
![3a](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/3a.png?raw=true)

_Last Part_
![3b](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/3b.png?raw=true)

## Activity 4
![4](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/4.png?raw=true)


## Activity 5
Functional Requirement: Course information about specific classes is displayed.

Improvement: Currently, this feature is available but in a very cramped, not obvious tabular form that makes it difficult to differentiate between pieces of information. The table needs formatting to make this much easier to understand. For example, the headers of the below table from Location to Delivery Mode are all squished together and should be spaced apart and separated with dividers.

![5a](https://github.com/gabriellemadden/ECE444-F2021-Lab3/blob/main/activity-proofs/5a.png?raw=true)


Non-functional Requirement: The user can specify one of Division, Department, or Campus to filter out courses. This is very rudimentary. I would like to add more course information to filter by and possibly allow the combinations of filters as well, so that users can develop searches that are very specific to their needs. Things students may want to filter by include time offered, majors, number of prerequisites, mode of delivery, etc.


# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
