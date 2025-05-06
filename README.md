# Link to GitHub repository with merged branches 
https://github.com/Aravindminfy/trainingminfy

# Screenshots showing the merge conflict
![Screenshot 2025-05-05 182219](https://github.com/user-attachments/assets/0dda5617-311e-4d02-883a-e589ca55e355)
![image](https://github.com/user-attachments/assets/82db53c3-7a88-4891-9a6d-4bd9f7bb5fc8)


# Screenshort showing  resolution process
![Screenshot 2025-05-05 195808](https://github.com/user-attachments/assets/51dbfe7b-3027-471c-9be4-c49310cc024e)
![Screenshot 2025-05-05 200214](https://github.com/user-attachments/assets/e27da1cc-ca2f-4a57-a843-a58c033ace26)

# Final Merged branchs 
![image](https://github.com/user-attachments/assets/e32d1c87-c183-4a2f-8227-8bb65c707173)

### Brief Explanation of How the Git Conflict Was Resolved

A Git conflict occurs when two branches modify the same part of a file, and Git cannot automatically decide which change to keep during a merge.

In my case:

- The `feature-subtract` branch added a `subtract()` method.
- The `feature-multiply` branch added a `multiply()` method.
- Both branches made changes in the same location in `calculator.py` (just after the `add()` method), which caused a merge conflict.

To resolve the conflict:

- I manually edited the file to remove the conflict markers and kept both the `subtract()` and `multiply()` methods.
- Alternatively, this could have been done using the VS Code merge tool (by selecting **Current + Incoming** and completing the merge).
- I then committed the resolved code to the `main` branch with the message:  
  `"Resolved merge conflict and added both subtract and multiply methods."`

As a result, both branches were successfully merged into the `main` branch, and all conflicts were resolved.
