# Weight-lift-counter-
I often tend to miss out on keeping track of my repetitions while training on weight based exercises which actually made me do this haha ;)


# SENSOR FUSION IMU - BNO055 (in the form of glove or attached to the weights)
Collects the data based on the hand movement while working on the weights and implied complimentary filters to obtain all-pass estimate orientations

# Prediction of exercise
A bayesan classifier to predict the exact exercise.
Exercises covered :-
1) BICEP CURL
2) LATERAL RISE
3) BENT OVER ROW

# REPETITIONS COUNTER

A Hidden Markov Model was used to segment weight exercises. Different parts of a repetition were mapped to different hidden states of the model. A segmentation was done by detecting repeating
patterns in the estimated state sequence.


