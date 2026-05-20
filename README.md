Homework One 

CS 898BA – Image Analysis and Computer Vision 

**Purpose:** To apply basic image analysis and processing techniques. 

**Situation:** You are working at Meta, and your supervisor’s supervisor walks in, gasping for air. You don’t often interact with him, so this visit is strange. He opens a folder on his personal computer and shows you an image he thinks is an alien, captured by his doorbell camera. You are not convinced and think he is just seeing things. He came to see you because he heard you took an image analysis course in college and wants you to clean up the image so it is easier to make out what is in it. 

---

Part 1: This is a stupid and wasteful use of your time, but you should probably at least pretend to work on it: 

* Create a git repository for a Python codebase using OpenCV named FirstnameLastname-CS898BA-Project1. 


* Create an initial commit with a “Hello World!” Script. 


* Keep track of all AI usage in a file named AI_Log.md. 


* Each entry should include the full prompt, the date and time the prompt was issued, the AI tool used to enter the prompt, a synopsis of the result, and any relevant design or code changes affected by the result. 



Here is a very silly example: 

The following table: 

| Date and Time | Prompt | Tool | Response Synopsis | Change |
| --- | --- | --- | --- | --- |
| 05/05/2026 12:00 AM | When is Cinco De Mayo? | ChatGPT | Today | Changed dinner plans. |
| 05/10/2026 3:15 PM | I totally forgot to buy my mom a gift and she is coming over!!! Please make an image of a handwritten letter telling her how much I love her. | Gemini | Happy Mother’s Day letter and scolding me for being terrible/ungrateful. | Set reminders of Mother’s Day and felt deep shame. |

* Perform incremental commits with updated code for each question with a quality commit message. 


* Ensure you include a comprehensive ReadMe file with code explanations, setup and execution steps, and your results, along with a discussion. 



---

Part 2: You know you should at least do basic analysis to get started, so you perform the following on the image: 

* Find and print basic image statistics of the original image (min, max, average, median, mode, skew, range, standard deviation, variance) 


* Find the histogram of the image and equalize it based on that histogram. 


* Save that equalized image to a new file. 


* You should now have 2 images. 


* Convert both the first image and the equalized image to greyscale, binary, and different color spaces (HSV, CIELAB, and HLS). 


* Save those images to new files. 


* You should now have 12 images. 


* Perform random affine transformations on each image (translation, rotation, scaling, shear). Save each of those images to new files. 


* You should now have 24 images. 


* Apply a Gaussian blur to each image using varying levels of sigma. Save each of those images to new files. 


* You should now have 48 images. 



---

Part 3: You decide that detecting the edges of the unknown figure would be useful, so you do the following: 

* Randomly create 4 equally sized subsets of the images from part 1. 


* Perform unique edge detection techniques on each subset: 


* Sobel 


* Laplacian 


* Canny 


* Prewitt 




* Provide an analysis of the pros and cons of each edge detection technique and perform an analysis of which of these techniques works best for this image set. 


* (Reminder – Canny may be the most used and applied, but it may not be the best in your case. Make sure your analysis fits your results.) 


* Save each image before and after adding edges, and output a random subset of 6 image pairs for your submission. 



---

Part 4: You officially get bored with this and go back to your actual job…..after watching a few dozen YouTube videos. 

* Submit your github repository link on BB. 



[Important!](https://www.youtube.com/watch?si=_oKzGwWlxC3cgcrH&v=SaA_cs4WZHM&feature=youtu.be) (Turn down your volume before clicking.)

[IMAGE DOWNLOAD FOR HW1](https://wichitaedu-my.sharepoint.com/:i:/g/personal/u577g584_wichita_edu/IQDhM0PY2yapTI1qxl_aPAHKAVPzCgBXEmIK3u-yQR3VP2I?e=NULzW5)

<img width="1017" height="555" alt="image" src="https://github.com/user-attachments/assets/1920f37b-f2b0-4816-88d0-d3e339a8df3d" />
