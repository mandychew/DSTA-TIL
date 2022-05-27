# 2022 DSTA-TIL
Team Track_Robot's codes for 2022 DSTA TIL Competition.  
## Task 1: CV Challenge
1. The training dataset provided will contain images of humans in various standing and fallen positions.  
2. You are tasked to create and train an Object Detection model to:  
    - Detect the bounding box coordinates of all humans in the images  
    - Classify the positions of all humans in the images (standing or fallen)  
3. You are allowed to use/include external datasets of your choice but you
need to cite your sources and abide by any copyright rules stated by the
data owners.  
4. The evaluation data will consist of images of humans in various standing and
fallen positions.  

### Evaluation of CV Challenge
1. The CV task will be evaluated using AP@[0.5:0.95] (rounded off to 4 decimal places) scores, the average AP for IoU from 0.95 to 0.95 with a step size of 0.05..
2. Your model’s outputs must be stored in a JSON file in the COCO format for evaluation. Below is a sample of an expected JSON file:  
  
    ![JSON file](./README%20images/example%20of%20JSON%20submission%20file.png)  

## Task 2: NLP Challenge
1. The dataset is a collection of audio clips with expressions of the following emotions: angry, fear, happy, neutral, sad.  
2. Your task is to train a model to perform speech emotion recognition.  
3. You will be provided a training set for your use. You are allowed to include
additional data to train your model.  
4. The evaluation data will consist of audio clips spoken in multiple languages.  
5. Majority of the evaluation data are in the intonation of Singapore English.  

### Evaluation of NLP Challenge
1. The NLP challenge will evaluated with [F1 score](https://www.wikiwand.com/en/F1_score) (rounded off to 4 decimal
places), the harmonic mean of precision and recall.  
2. Ensure that the submissions are in .csv with format matching the provided sample (spreadsheet with no headers, sorted in ascending order by the first column with the correct number of entries). Below is a sample of an expected csv file:  

    ![CSV file](./README%20images/example%20of%20CSV%20submission%20file.png)