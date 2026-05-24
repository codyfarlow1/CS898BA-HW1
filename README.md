Homework One 

CS 898BA – Image Analysis and Computer Vision 

**Purpose:** To apply basic image analysis and processing techniques. 

**Situation:** You are working at Meta, and your supervisor’s supervisor walks in, gasping for air. You don’t often interact with him, so this visit is strange. He opens a folder on his personal computer and shows you an image he thinks is an alien, captured by his doorbell camera. You are not convinced and think he is just seeing things. He came to see you because he heard you took an image analysis course in college and wants you to clean up the image so it is easier to make out what is in it. 

---

Part 1: This is a stupid and wasteful use of your time, but you should probably at least pretend to work on it: 

  1.  Create a git repository for a Python codebase using OpenCV named FirstnameLastname-CS898BA-Project1. 


  2.  Create an initial commit with a “Hello World!” Script. 


  3.  Keep track of all AI usage in a file named AI_Log.md.
  
  
    i.  Each entry should include the full prompt, the date and time the prompt was issued, the AI tool used to enter the prompt, a synopsis of the result, and any relevant design or code changes affected by the result. 


Here is a very silly example: 

| Date and Time | Prompt | Tool | Response Synopsis | Change |
| --- | --- | --- | --- | --- |
| 05/05/2026 12:00 AM | When is Cinco De Mayo? | ChatGPT | Today | Changed dinner plans. |
| 05/10/2026 3:15 PM | I totally forgot to buy my mom a gift and she is coming over!!! Please make an image of a handwritten letter telling her how much I love her. | Gemini | Happy Mother’s Day letter and scolding me for being terrible/ungrateful. | Set reminders of Mother’s Day and felt deep shame. |

  4.  Perform incremental commits with updated code for each question with a quality commit message. 


  5.  Ensure you include a comprehensive ReadMe file with code explanations, setup and execution steps, and your results, along with any relevant discussion. 

---

Part 2: You know you should at least do basic analysis to get started, so you perform the following on the image: 

  1.  Find and print basic image statistics of the original image (min, max, average, median, mode, skew, range, standard deviation, variance)
  2.  Find the histogram of the image and equalize it based on that histogram.
  3.  Save that equalized image to a new file.
  4.  You should now have 2 images.
  5.  Convert both the first image and the equalized image to greyscale, binary, and different color spaces (HSV, CIELAB, and HLS).
  6.  Save those images to new files.
  7.  You should now have 12 images.
  8.  Perform a single random affine transformation on each image (you should perform 12 total transformations - 1 for each image). Affine transformations can be translation, rotation, scaling, or shear as long as each is unique in either transformation type or transformation value (rotate 90 degrees vs rotate 186 degrees). No two images should be transformed in the exact same way. Save each of those images to new files.
  9.  You should now have 24 images.
  10.  Apply a Gaussian blur to each image using the levels of sigma: 0.5, 1.0, 1.5, 2.0, 2.5, 3.0, 3.5. Discuss how the level of sigma changes the image. Save each of those images to new files.
  12.  You should now have 192 images.

---

Part 3: You decide that detecting the edges of the unknown figure would be useful, so you do the following: 

  1.  Randomly create 4 equally sized subsets of the images from part 1.

    Each subset should have 48 images.

  2.  Choose a subset to use in the remaining steps.

  3.  You should now have 48 images.
    
  4.  Perform these edge detection techniques on that subset:

    a.  Sobel
    b.  Laplacian
    c.  Canny
    d.  Prewitt

  5.  Discuss the pros and cons of each edge detection technique and perform an analysis of which of these techniques works best for this image set.

    Reminder – Canny may be the most used and applied, but it may not be the best in your case. Make sure your analysis fits your results.
    
  6.  Save each image before and after adding edges with each technique.
     
  7.  You should now have 240 images.
  
  8.  Create 48, 5-image plots of the input image (from the start of part 3) next to the edge-detected images and output 6 random plots to add to the readme. Your plots should look similar to this:

<img width="1192" height="1208" alt="image" src="https://github.com/user-attachments/assets/5648aeb3-16b3-4592-aaf7-26d708dfa4ef" />



---

Part 4: You officially get bored with this and go back to your actual job…..after watching a few dozen YouTube videos. 


**Submit your github repository link on BB.**

---
  
**[HOMEWORK ONE IMAGE DOWNLOAD](https://wichitaedu-my.sharepoint.com/:i:/g/personal/u577g584_wichita_edu/IQDhM0PY2yapTI1qxl_aPAHKAVPzCgBXEmIK3u-yQR3VP2I?e=NULzW5)**

<img width="1017" height="555" alt="image for homework 1" src="https://github.com/user-attachments/assets/1920f37b-f2b0-4816-88d0-d3e339a8df3d" />
