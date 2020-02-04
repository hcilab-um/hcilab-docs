# Study Design

This page will outline the necessary actions before run your studies as well as what to do afterwards.

## Quick Links
* [Example Study Script](https://drive.google.com/file/d/1A5-DR3LoLZ9bCM5VMQ-79dG9q7WGdWn1/view?usp=sharing)

## Ten Commandments

1. Conduct a literature review (>40) to explore previous studies
2. Obtain approval for your research goal/question/hypothesis from Dr. Irani/Yumi
3. Develop a session script
4. Conduct a complete run-through with a lab member
5. Hand in your predicted results with actual numbers
6. Propose the study to the lab (≈10 mins for the presentation; ≈15mins for feedback)
7. Obtain ethics approval (up to 5 weeks for the full ethics & 1 week for the amendment)
8. Obtain gift cards at least one week before the study
9. Ensure to run Ishihara's Color Blind test
10. Share all the study material with the collaborators (e.g., google drive)

## Idea/Motivation

If you have an idea you would like to test, there are a few things you should do before you design your study. Most importantly you should be able to effectively communicate what your idea is and have sufficient literature review to ensure that what you are testing is novel and has not already been done. Once you believe that you have reviewed enough to proceed, create a few slides explaining your idea and present it to Pourang and Yumi for approval. 

## Literature Review

Try to review as much literature as possible to extend and support your research idea. Use Google Scholar and the various digital libraries to research your subject and see if your idea has been attempted. If you are extending someone elses research, make sure you have enough literature to support your motivation. You have to convince others that your idea is a solid contribution to the field. There is no cap on how many papers and projects you should review. Keep up with the pubilcations even as you are running your study to be up-to-date with your research area since you are most likely not the only one looking into the idea.

## Designing a Study

Once your idea has been approved, its time to come up with how to test your idea. Each study is most likely going to be different, so this section will outline some general tips on getting started.

### Variables

One of the first things you should be thinking about is what you are measuring and how you are going to measure it. Take the time to learn about dependent and independent variables, that way you can think about what variables you will be testing and what variables you have to control. For example, if you are going to measure the performance of a task, you would most likely be measuring `time` and `accuracy`.

### Study Plan

Once you determine your variables, next create a study plan that you can reference when you are implementing your application. Try to include **as much details as possible**, so you can effectively communicate your study design. **THIS WILL BE IMPORTANT FOR ETHICS**

Here is an example of a simple study plan:

```
Purpose: To determine which condition yields the best game performance 

4 Conditions:
- Visual stimuli with visual feedback
- Audio stimuli with audio feedback
- Visual & Audio stimuli and Visual & Audio feedback
- Visual & Audio stimuli and Visual & Audio feedback -> Audio stimuli with audio feedback only

Design: Between Subject Study

Number of participants: 6 - 10 per condition

Number of Trials: 10 - 20 trials of 20 compressions per trial, with a break midway to test potential skill regression as well as give the participant rest.

Steps:

A. Visual: Participant will wear the Hololens and play the game like normal with visual cues of the fox and the crate, and they can see whether or not they have hit or missed a target and whether they have overshot/undershot their target as well. 

B. Audio: Participant will wear the Hololens and attempt to play the game with only audio cues. A few different sounds will be played to determine whether or not they have hit or missed a target and whether they have overshot/undershot their target as well. Possible sounds include:
1. End of Each Trial: Signal the end of each trial - https://freesound.org/people/LittleRobotSoundFactory/sounds/270333/
2. Ready for next trial: Signal the ready for next trial - https://freesound.org/people/LittleRobotSoundFactory/sounds/270330/
3. Jump Signal: Cue to jump at the target - https://freesound.org/people/jalastram/sounds/317732/
4. Jump: Cue that the bag has been compressed - https://freesound.org/people/n_audioman/sounds/273566/
5. Missed Target (Negative Sound): Missed target feedback - https://freesound.org/people/n_audioman/sounds/273766/
6. Hit Target (Positive Sound): Hit Target feedback - https://freesound.org/people/cubix/sounds/124382/
7. Overshot (Negative Sound): The target went too high, less pressure required - https://freesound.org/people/SamsterBirdies/sounds/363920/
8. Undershot (Negative Sound): The target went too low, more pressure required - https://freesound.org/people/MentosLat/sounds/417486/
9. Score! (Positive sound): Target scored a point. https://freesound.org/people/LittleRobotSoundFactory/sounds/270304/

C. Visual + Audio: Participant will be able to see the game and hear the cues.

D. Visual + Audio -> Audio: Participant will do the first half of the study with the Visual + Audio and then transition into an Audio only feedback method.
Qualtrics Questionnaire to determine the comfort of the system, etc…


Major Dependent Variables
Time Hit Rate: If a target gets hit, this means that the user has accurately timed their compression. This should be calculated by Hit Correctly /Total crate. Note that this variable (i.e., Timing) is independent from strength which I describe next. Hence, as long as the crate is moved, the response is taken as “Hit”  

Strength Hit Rate: Strength is measured by the amount of pressure emitted by each compression; participants will be receiving visual and/or audio feedback in order to recognize how much pressure they are emitting (too much vs. too little vs. just right). Again, Hit Correctly /Total crate yields the Hit rate. This is independent from the timing variable. Thus, any response that stays within the proper range should be recognized as a “hit.” 

True Hit Rate: This looks at both response strength and timing. Only those response with accurate timing and strength are recognized as “Hit”. Likewise, Hit Correctly /Total crate yields True Hit Rate. 
```

Your plan will iterate and change as you meet, discuss, and present your idea with Pourang, Yumi, and the lab for feedback. **THIS WILL BE IMPORTANT FOR ETHICS**

### Study Script

While implementing or after implementining your study application, create a study script to keep each study session consistent. When running a study, the script is important as it helps with the reproduction of the study. Even subtle changes to the script or the way you interact with the participant can affect the data that you are trying to obtain. An example of a study script can be found [here](https://drive.google.com/file/d/1A5-DR3LoLZ9bCM5VMQ-79dG9q7WGdWn1/view?usp=sharing). **THIS WILL BE IMPORTANT FOR ETHICS**


## Pilot Studies

Once your design, implementation, and study is at a state where you can start testing your idea you are required to run your study with some lab members. Pilot studies help you determine things like how long your study will take, what needs to be changed, where your application fails, amongst many other things. Furthermore, it will help you practice your script and give you a chance analyze the data before running it with general participants. **IT IS IMPORTANT TO RUN AN ANALYSIS OF THE PILOT STUDY TO SEE IF YOU'RE MISSING ANYTHING!** This will also allow you to see look at any potential trends when you run the actual experiment.

## What's Next?

While you are running your pilot study it's important to already have documents in place to apply for [ethics approval](research/ethics). Once you have ethics approval, you can officially [run your study](research/runningstudy). 