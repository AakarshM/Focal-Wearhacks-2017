# Context
* __App Name:__ Focal
* __Platform:__ Android w/ Muse Headband
* __Where:__ [WearHacks Kitchener 2017][1]
* __3rd place prize winner__

# Team Members
Aakarsh Madhavan, Andy Su, Carla Leal, Kenneth Zeng

# Inspiration
Finals are coming up and we have trouble focusing on revision. However, it's hard to gauge the efficiency of revision, it's all subjective. We have always heard of the guy who has "revised for like 8 hours" when in fact they've watched Youtube for 3, browsed Reddit for 3 and maybe revised for like 30 minutes. We wanted to create something that analyzes how efficiently we are revising. The metric that we chose was concentration - in the form of measuring brain waves. Our app shows real-time analytics of how well we are concentration and provides this data in the next session to compare how well we are paying attention.

# What it does
The app retrieves brainwave data from muse headband and analyzes different types of waves. The data is stored on a database on Firebase for future analyzing purposes. Constructs graphs to compare current session to the last session.

# How we built it
First, connect Muse headband to a phone using Bluetooth. After the phone is connected with Muse headband, it will return various types of brainwaves including Alpha waves and Gamma waves. Then, the phone constructs a real-time graph by using GraphView, which is a built in graph function in Android Studio. Not only this, it will also send data to the Firebase database for storing purposes. The stored information is useful when it come to comparing results.

# Challenges we ran into
Some challenges we ran into include not being familiar with Muse API, interpreting the results of brainwaves, and constructing a real-time graph.

# Accomplishments that we're proud of
Real-time graph, storing data in database, analyzing and retrieving a large amount of data (big data).

# What we've learned
I tried a lot of different cool hardware which I have never been able to experience before. I have only really had experience with software development. At this event, I mostly learned teamworking skills, communication skills, advanced Android Studio programming knowledge and the usage of Muse headband.

# What's next for focal
Right now, it only has basic functionality. We hope to include more functionality and analysis such as the ability to compare concentration between different subjects - for example, between English & Math (students may study preferentially). We may also switch libraries for the graphing to give an aesthetic upgrade to the app.


[1]: https://devpost.com/software/focal-ziyk7x "Focal @ Wearhacks"
