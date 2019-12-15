## VMASC Internal Project ##

### Twitter Sentiment Library Project ###
This project was designed and built in about two weeks. We were looking at a way to engage students who were in the library. We predetermined 9 hashtags that were directly associated with 9 departments at the university and asked students to say anything they wanted about their department.

We used a series of open source libraries to help scrape twitter data by predetermined hashtags and then IBM to run its sentiment analysis - based on IBM's result we then used a visualization system to display the tweet, remove the user handle, and display the shape of their tweet, their tweet then impacted a board on the master visualization that caused a 'break' in the current visualization.

### Unity ###
*Required Packages*
>TextMesh Pro
>LightWeight RP 6.9.2

This repository contains some sample videos of what the application did and the 3D content we used to represent the sentiment. The actual project source cannot be released at this time.
>The core project used LinqToTwitter to scrape the data
>IBM Sentiment/Tone Analyzer to Process the text
>The work done by Zan in Hi.Stamen
>Quad Tree algorithm to break the square tile into other sections - X,Y Coordinates were Time and Sentiment confidence
>Blend Shapes to take a sphere (0) shape into one of the 4 emotions(1): Anger, Joy, Fear, & Sad. You can blend between all four and get some odd shapes, see the blend video for how this is done.

#### Project Resources ####
[ODU YouTube Video Explaining the Project](https://www.youtube.com/watch?v=L7-TkfYY18I)

[Visualization Concept Derived From this work](https://hi.stamen.com/the-shapes-of-emotions-72c3851143e2)

[LinqToTwitter](https://github.com/JoeMayo/LinqToTwitter)

[IBM Watson Tone-Analyzer](https://www.ibm.com/watson/services/tone-analyzer/)

[IBM Unity SDK](https://github.com/watson-developer-cloud/unity-sdk)

[Unity Manual Blend Shapes](https://docs.unity3d.com/Manual/BlendShapes.html)

##### Contact #####
[John Shull](JShull@odu.edu)