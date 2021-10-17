# ECE444 Lab 5: Front End Design
Completed by Jay Bihola


### Acknowledgements
This repo is a clone of https://github.com/nelaturuk/education_pathways

### Activity 1

![Activity 1 screenshot](https://user-images.githubusercontent.com/39041724/137636309-3324c0ea-00a4-4231-ac13-6b77368925d5.png)


### Activity 5
![Search Page](https://user-images.githubusercontent.com/39041724/137636316-001b84b7-5aa3-40c3-b82b-6dea7921ac2c.png)
![Search Results](https://user-images.githubusercontent.com/39041724/137636318-3ca0be68-ab78-438b-8fb9-ab7dc9a1509c.png)

### Activity 6
The new UI is much more modern and user friendly as compared to the old UI, which looks very dated and hard to read. The main difference is the spacing which makes the various elements of the UI much more easy to read and understand. In the new UI, this has been solved with ample padding and spacing between elements, which was added through the CSS. The spacing allows for distinction between text boxes on the input fields as well as results on the results table.


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
