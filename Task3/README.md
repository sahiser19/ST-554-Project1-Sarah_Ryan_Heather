Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Feedback giver #1: Ryan
  + I think you have a good outline and narrative flow in your notebook. Try to briefly explain additional terms when you first discuss them, like simple vs multiple linear regression, cross-validation, and why we’re using them
  + Your approach to data cleaning, including dropping the right columns, replacing -200 with NaN, grouping by Date, and adding a Day column, all appear to be correct.
  + Possible error fixes:
      + The Value error saying “expected a 2-dimensional container” could be because your x_test is passed as a series. Try to see if setting `x_test = X.iloc[[D1]]` # (double brackets) will work, because then it will be a single row dataframe.
          + If you can get this approach to work, I think it would be better than the *argument approach you used in MSE2
      + Also, since your function is for finding MSE, you can remove the np.sqrt (this would be correct for RMSE)
      + For your CrossVal function, your first line, Days = … might have issues iterating; it wraps the loop in a list and only runs once. You could try:`for i in range(Start_Day, End_day+1)`
          + SLR=[] overwrites the function parameter SLR=False; use a different variable name for SLR.
          + Also, try using an f-string for your print statement, like `print(f'The SLR MSE is {SLR_Mean} and the MLR MSE is {MLR_Mean}')`
          + Finally, I think your logic is backwards; it should be SLR_Mean < MLR_Mean, since a lower mean squared error is better!
  + Include results at the end, discussing the two models and the final model fit!



- Feedback giver #2
  + item
