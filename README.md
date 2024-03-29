# HackerEarth Deep Learning Challenge: 'Tis STILL the season to be jolly

### Problem statement
You work for a social media platform. Your task is to create a solution using deep learning to discern whether a post is holiday-related in an effort to better monetize the platform.

### Task
You are given the following six categories. You are required to classify the images in the dataset based on these categories.
 - Miscellaneous
 - Christmas_Tree
 - Jacket
 - Candle
 - Airplane
 - Snowman
 
### Data Description
This data set consists of the following two columns:

<img width="300" alt="Screen Shot 2021-01-29 at 4 17 38 PM" src="https://user-images.githubusercontent.com/53478586/106265802-9367f680-624d-11eb-915a-12fe437fe1a5.png">

### Data Format
The data folder consists of two folders and one .csv file. The details are as follows:
train: Contains 6469 images for 6 classes
test: Contains 3489 images
train.csv: 3489 x 2

### Submission Format
You are required to write your predictions in a .csv file and upload it by clicking the Upload File button.

### Sample Submission
Image,Class
image3476.jpg,Miscellaneous
image5198.jpg,Candle
image4183.jpg,Snowman
image1806.jpg,Miscellaneous
image7831.jpg,Miscellaneous

### Evaluation Matrice
<img width="758" alt="Screen Shot 2021-01-29 at 4 17 29 PM" src="https://user-images.githubusercontent.com/53478586/106265819-97941400-624d-11eb-879a-0577769b3517.png">
 
### Acknowledgement
Link To Contest --> https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-holidays/

---
# My Solutions (Rank: 120, Top 3%)
1.  Attempt 1
    - SCORE: 88.90237
    - Used transfer learning in Keras and fine-tuned an InceptionResNetV2 model
2. Attempt 2
    - SCORE: 90.94382
    - Used transfer learning in Keras and fine-tuned an InceptionV3 model
