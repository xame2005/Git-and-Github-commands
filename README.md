# Git-and-Github-commands
Git and Github commands

## Assignment

You must write all your commands inside instructions.sh and push to the main branch.

1. Create an empty file called robot.txt
1. Create 4 different branches called dev, stg, qa and prod.
2. Change your branch to dev and append the text "walking()" to the file. Commit and Push your Changes (CaP).
3. Rebase the dev branch on main and prod branch. (CaP)
4. Change to stg branch, create a new file called robot_test.txt and append the following text: "walking_test()\nTest complete!!". (CaP)
5. Rebase the stg branch on main and qa branch. (CaP)
6. Change to qa branch, append to the robot_test.txt file the text "walking_acept_test()\nUser accepted the changes!!". (CaP).
7. Merge the qa branch on main and stg branch. (CaP).
8. Change to prod branch, append to the robot.txt file the following text (CaP): 
```
SOME_PROD_VAR='PROD VALUE'
ROBOT_CREDENTIALS='SOME CONFIDENTIAL ROBOT CREDENTIALS'
WALK_CONFIG='SOME PROD WALKING CONFIGURATION'
```
9. Create the branch dev_feature123 and also dev_feature321.
10. Change to branch dev_feature123, append robot.txt the text "left_leg_quick_walking()". (CaP)
11. Change to main branch and merge the branch dev_feature123 .
12. Change to branch dev_feature321, append robot.txt the text "right_leg_quick_walking()". (CaP)
13. Change to main branch and try to merge the branch dev_feature321.
14. Resolve the conflicts.
15. Delete the bug branches.
16. Create the branch dev_bug1 and also dev_bug2.
17. Change to branch dev_bug1, append robot.txt the text "complete_translator()". (CaP)
18. Change to main branch and merge the branch dev_bug1.
19. Change to branch dev_bug2, append robot.txt the text "incomplete_translator()". (CaP)
20. Change to main branch and try to merge the branch dev_bug2.
21. Resolve the conflicts.
22. Delete the bug branches.
23. Create the branch dev_bug44 and also dev_bug45.
24. Change to branch dev_bug44, append robot.txt the text "noisy_mic_recording()". (CaP)
25. Change to main branch and rebase the branch dev_bug44.
26. Change to branch dev_bug45, append robot.txt the text "best_quality_mic_recording()". (CaP)
27. Change to main branch and try to rebase the branch dev_bug45.
28. Resolve the conflicts.
29. Delete the bug branches.
