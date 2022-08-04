# Pose Fitter
Counts pushup currently from video input

https://user-images.githubusercontent.com/81124258/182865028-cbf02d09-c70d-4779-9bfe-0d60c3e1a637.mp4

*Working*
Based on angles calculates the direction of movement and contraints and when both directions have been checked the count increases.

*Errors and shortcomings*
1.Hard coded angles : Difficult to be set up by non technical person. Improvement might be automatic angle constraints checker
2.Angles based on single video: The angles have been taken from 2 videos for left and right side push ups grown adults. If a child performs exercise erronous result is given.
3.No horizontal or vertical position checking: If a persons movements satisfy the angle constraints no matter they are standing or doing it properly, it would show as proper pushup.
