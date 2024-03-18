# Optimal_Player_Substitution_Strategy

## Problem Statement:

● Decision-making on substituting players between matches is 
  done only manually by coaches.

● In this Era, coaches use their analysis and experience to predict 
  whether to substitute a player or not.

● No Individual players' performance is being monitored by the 
  latest Models.

● The latest Models use Statistical Data to analyze the game.


## Solution:

1) First we have video as our input and then we convert it into frames which 
will be used for further processing. These frames will be fed into our 
detection system which will use three Famous detection models YOLOv5, 
YOLOv7, and YOLOv8. Detection models will detect the usable characters 
from the frames like (players, referees, and balls). 

2) Then there will be a comparison between the detection 
models and the best model (YOLOv5 in our case ) will be 
attached to another system called ByteTrack which tracks 
the detection frames and presents it as a video in front of us

3) In parallel, it also classifies the players by assigning unique 
numbers to the players during the tracking and that 
identification will be used for further analysis

4) we will calculate two parameters that are distance 
traveled by the player (stamina) and how much time 
the player was in ball possession

5) At last, we will calculate the performance of the 
player based on these two parameters

## Result

![1](https://github.com/usama-baloch/Optimal_Player_Substitution_Strategy/assets/83680012/3b062ddb-5c72-4a7b-b809-e69bec8dedc3)
