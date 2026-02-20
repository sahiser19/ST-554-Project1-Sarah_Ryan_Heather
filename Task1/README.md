Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Updates
  + Provided github branch to Ryan and Heather but I did not execute the invitation to the collaborators and needed to resend the invite.
  + 2/17 waiting for pushes to review code.
  + Added hard copy file to github repo. Need to discuss with group members about how to pull data if there was ever an update. 


- Feedback giver #1: Ryan
  + Your Notebook looks good! I think you have a lot of the ‘meat’ of this task finished, your RMSE function and gd functions look accurate!
  + Grid search for the constant and the SLR appear to be implemented correctly, including the specified b0/b1 bounds
  + You should delete the ‘featured examples’ section at the bottom (I believe this is from a colab template?)
  + Try to make your notebook more narrative-focused, from the project guidelines: “A narrative (a spoken or written account of connected events; a story) done in markdown should exist in all Notebooks for full credit.” “The audience you are writing for is someone who understands programming and very basic statistics, but would need you to provide details and an explanation of what you are doing to understand it.” 
      + For example, at the start of the notebook, give a brief interview on the goals of this analysis, briefly explain what a gradient descent algorithm is, explain terms like root mean squared error (rmse), and why we want to minimize it.
      + I would also add more in-depth explanations for some of the functions (especially the last three), giving an overview of what they do, the parameters they take in, how they are useful/can be applied, etc.
  + As you acknowledged, the “best_constant_by_grid function could be cleaned up (or combined with the make_c_grid_from_quartiles function?).
  + For consistency, I think you should drop missing values (-200 observations) across all columns instead of just the CO and C6H6 columns
  + I think you should also test your functions for gd_constant and gd_slr with some values and print the output (could also help to find errors or make sure your functions don't take super long to run).
  + May want to state the optimal constant prediction (c) explicitly? From this part in the guidelines: “Run your algorithm on the C6H6(GT) variable and determine the optimal constant prediction.”



- Feedback giver #2
  + item
