# lab5: Deep learning micro project

## Lab5 Goal
Lab5 is a micro-project. The goal in this lab is to improve the finger digits classifier.

You may choose one of the three approaches:
1. Controlled environment:
  - Acquire more/other training and validation data with lab2 tools. 
  - More specifically, choose a controlled environment with uniform background, constant lighting, only hand in field of view, etc.
  - Retrain a model using your lab3 approach. 
  - Re-evaluate production performance.
1. Share and grab data:
  - Copy your training and validation data to a folder `digits_zzz` (`zzz` your choice of number) on [UofC onedrive](https://uofc-my.sharepoint.com/:f:/g/personal/yves_pauchard_ucalgary_ca/Eswi4KbJsmlMl8M4G7lM5ioBM_TIpwilEV9x86wsBcaTRQ?e=dvJXH5)  
  - In turn, grab any data present in the onedrive folder.
  - Combine and retrain a model with this larger dataset. 
  - Re-evaulate production performance.
  - Note that the data in this folder is available under a [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
1. Different architecture:
  - Build your own architecture using Chater 13 and Chapter 14 ideas.
  - Or, follow [this tutorial](https://walkwithfastai.com/vision.external.timm) to access other pre-trained architectures.
  - Retrain a model using your lab3 approach. 
  - Re-evaluate production performance.

## What to hand in
- A notebook `lab5-micro-project.ipynb`:
  - *Introduction* Describe the approach chosen, reason for choosing it and how you implemented it.
  - *Model Code* model training and results
  - *Summary and Conclusion* Summarize your results, re-state lab3/lab4 results and comment on changes.
  - *Reflection*
- Keep code clean, comment/document and remove any unnecessary cells in the notebook.

During development, save progress with git and use descriptive commit messages.

Hand in: git push all files, verify on github, submit url on D2L.

**Important:** Do **not** commit image data to github. Images do **not** need to be handed in.
