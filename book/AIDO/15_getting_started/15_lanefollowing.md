# Lane Following Quickstart {#quickstart-lanefollowing status=ready}

<div class='requirements' markdown='1'>

Requires: You have [set up your accounts](#cm-accounts).

Requires: You have [the software requirement](#cm-sw).

Requires: You have [made a submission](#cm-first).

Result: You have made a submission to the Lane Following AI-DO challenge, and you know how to try to make it better.

</div>

The objective of this quickstart guide is to describe all of the "strawman solutions" so that you may use your desired framework, and then describe the baseline implementations as options for ways to try to build a better entry.

## Do a submission by following one of the strawman solutions

* [Random template](#minimal-template)
* [Tensorflow template](#tensorflow-template) 
* [PyTorch template](#pytorch-template) 
* [ROS template](#ros-template) 

Congrats! you have now made a submission, but it probably wasn't very good (unless you got very lucky).

## Try to make your score go up

Now is when you might want to take a look at [](#part:aido-rules) which describe in detail how your score is generated for the specific challenges. For the lane following challenge,  we are currently offering 4 suggested methods to do this (our baseline templates for these options are at various stages of readiness but will be getting updated very soon):


* Use ["classical" robotics and ROS](#ros-baseline)
* Use [reinforement learning](#embodied_rl)
* Use [imitation learning from data generated in the simulator](#embodied_il_sim)
* Use [imitation learning from data from real robots](#embodied_il_logs)
  
Of course you may also choose to use these methods in combination. 

## Try one of the harder challenges 

Like [LFV](#lf_v) or [LFVI](#lf_v_i) or run your submission [on your Duckiebot](#lf_duckiebot).
