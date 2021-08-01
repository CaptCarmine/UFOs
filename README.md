# UFOs

## Overview

I am following up on Dana's dynamic web page, and adding filter logic to allow for filtering on multiple criteria. I am going to do that by creating a function which finds when data is added, and applies logic to read for that input.

## Results

1. The images below show the average weather of Oahu, in June and December.
2. June has an average weather of 74.9 degrees, which is a great temperature for a Surf/ Ice cream shop, and even better the average temperature in December is only 3 degrees lower.
3. Following the other data points you can see that even at the 25% the temperature only deviates about 2 degrees away from the mean, not even 1 full standard deviation away.
4. December does have a much lower minimum temperature, but that does not have a large on any other metric.

### Results Example

![Searching_Example](https://github.com/CaptCarmine/UFOs/blob/main/static/images/Filter_images.png?raw=true)

## Summary

This is a great first draft of a working web page, however there is very little in the way of input validation. All the data needs to be put in a specific format to work correctly.

I would fix this by instead of having users do free form input, have a drop down for states, and calendar drop down for dates.

for city and shape you can add logic that will give an error if their is no data matching with what the user input.
