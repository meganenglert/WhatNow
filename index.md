# [Enter the site here!](https://meganenglert.github.io/WhatNow/homepage)

# WhatNow
WhatNow will be a web app meant to help individuals who struggle with executive function and time management. Its goal is to answer the question of "Well, what do I do now?"

## Background
According to [Harvard University's Center on the Developing Child](https://developingchild.harvard.edu/science/key-concepts/executive-function/), "executive function and self-regulation skills are the mental processes that enable us to plan, focus attention, remember instructions, and juggle multiple tasks successfully." 

When presented with many tasks, individuals struggling with executive function skills will often find themselves in a state of task paralysis. They may have difficulties stopping one task and beginning work on another or they may struggle to prioritize their list, becoming overwhelmed and unable to get any task at all done.

I personally experience this, and it makes my life as a student very difficult. When I attempt to juggle long assignments, short tasks (like responding to emails), and taking care of myself and my home, I often end up getting absolutely nothing done.

## A Solution?
However, I have very recently found a strategy that works for me: a random number generator.

I start by simply making a to do list. Then, I number each item, giving tasks with higher priorities multiple numbers to increase the probability that they will get selected. An example list might look like this:
- 1,2 - Take out the trash
- 3 - Email professor about grade issue
- 4,5,6 - Read pages 1-30 of *Art in Tibet* due tomorrow!
- 7 - Write discussion post
- 8,9 - Clean guinea pig cage

I then go to any random number generator, set the maximum, and generate until I get a number of a task I have not yet completed. 

## Let's Talk About WhatNow
The goal of WhatNow is to combine my piece of paper and random number generator and package it into one, cohesive web app interface.

I have scoured the internet for the perfect program to manage my tasks, but I never successfully found one with all of the features I wanted, so I will instead be making my own.

## Basic Features

These features are the core of WhatNow's functionality and will be implemented first.
- User-friendly `Add a Task` interface to enter a task name and its priority.
- `Pick a Task` button that will randomly select a task, weighted by priority.
- Some form of `Complete` button or checkbox that will allow the user to mark a task as complete.

## Stretch Features
These are ideas for some of the features I could add that would make WhatNow much more powerful and unique.
### Storing Tasks
Since WhatNow is a web app, the interface and tasks will completely reset when the page is refreshed. Ideally, I'd like to fix this by making some way to "log-in" that will store your tasks and their statuses between visits to the site.
### Tag System 

This system would allow users to tag their tasks using the `Add a Task` interface. They can then filter the results of `Pick a Task`, preventing the disruption and distracting caused by having to hit the `Pick a Task` button 10 times before finding something you can actually do. While I would like to allow for custom tags, some ideas for pre-made tags are as follows:
- Location: Are you running errands and have time to pick up a few things you've been meaning to get? Or are you trudging through a pile of work you have to be at your desk to do?
- Category: Do you want to focus on getting your house cleaned up? Or do you *really* need to get through your inbox?
- Focus-level: Do you want a task you can do while watching TV? Or are you feeling focused and ready to finish some of your more difficult tasks?
### Time Tracking
This system would allow a user to approximate the amount of time a task will need when entering it into the system. With this system, a user will be able to filter for tasks of a certain length (minimum, maximum or within a range) and view the total time estimated for all tasks within a tag.

### [Jump back to my Portfolio Home Page here!](https://meganenglert.github.io/CISC275/)