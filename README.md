# cvexploder

Generates a single standalone webpage, with all Javascript and style embedded, which forms an exploded CV with interactive elements to highlight keywords and skills.

## Pre-requisites

EJS

## Usage

The logic for generating the final CV is all contained in the template, so generating a file is as simple as populating your own json file based on the sample provided and then using EJS to create the webpage:

	ejs src/templates/exploded-cv.ejs -f sample-data.json -o cv.html
  
*TODO - document JSON fields, maybe in sample doc?*