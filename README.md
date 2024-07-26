# Precision Fertilization using the YOLO model
## Motivation Behind the Project
In Indian agriculture, farmers typically focus on applying a specific amount of fertilizer per acre of land. We aim to make an AI model that targets fertilization at the level of each plant or crop. This approach significantly reduces the amount of fertilizer used by about 56%, as stated in a BBC interview, thereby lowering costs and improving soil quality.  
  
Our model has the potential to reduce costs by Rs.20,500 per acre every year according to the research paper- Energy Consumption Pattern in Wheat Production in Sindh Pakistan by Memon, Noor & Noonari, Sanaullah & Laghari, Majid & Pathan, Maria & Khajjak, Akbar & Memon, Zarmina & Khan, Danyal & Pathan, Amber & Sial, Sajid. (2015).

## Data Collection
We manually collected data from a local park to train our data. The augmented data set can be found under the DatasetForTraining directory. A total of 70 images can be found, which includes both the validation and training set. The images were collected over both day and night time.  

## Directory Structure
* **DatasetForTraining:** Contains the augmented dataset with 70 images for training and validation.
* **PythonNotebook:** Contains two sets of code:
    * **OpenCV.ipynb:** Uses the pre-trained model for live data prediction. It also determines which fertilizer machine node to spray and when to spray using some mathematical calculations.
    * **Training YOLO model.ipynb:** Contains the code used for training the custom YOLO model.
      
## Detailed Documentation
Please take a look at the accompanying PPT for detailed documentation of the entire project.


