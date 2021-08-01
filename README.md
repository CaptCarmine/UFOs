# UFOs

## Overview

I am following up on Dana's dynamic web page, and adding filter logic to allow for filtering on multiple criteria. I am going to do that by creating a function which finds when data is added, and applies logic to read for that input.

## Results Instructions

The images below show the empty filter options. To be able to filter on any of the fields you need to copy the format, as seen in the placeholder.

![Empty fields](https://github.com/CaptCarmine/UFOs/blob/main/static/images/Images_empty.png?raw=true)

Date needs to be in the format of ##/##/####, indicating month day and year.
for the other fields you need to put in the information you are looking for without quotes.
as an example if you put state = ca , and Shape as triangle you will see the results as seen in the Results example.

### Results Example

![Searching_Example](https://github.com/CaptCarmine/UFOs/blob/main/static/images/Filter_images.png?raw=true)

## Summary

This is a great first draft of a working web page, however there is very little in the way of input validation. All the data needs to be put in a specific format to work correctly.

I would fix this by instead of having users do free form input, have a drop down for states, and calendar drop down for dates.

for city and shape you can add logic that will give an error if their is no data matching with what the user input.
