# Dish-from-Ingredients
The project aims to suggest dish from the image of available ingredients.<br />
This uses the following libraries and dependencies :<br />
-> Bing Image Downloader for Dataset<br />
-> Basic steps of Data Augmentation using Keras<br />
-> GroundedSAM for auto-annotations if images<br />
-> YoloV8 for Object Detection<br />
## Dataset
For Ingredient Detection : <br />
https://www.kaggle.com/datasets/nishchaygarg/food-ingredients-dataset?rvi=1 <br />
For Recipies from Detected Ingredients : <br /> 
https://www.kaggle.com/datasets/saldenisov/recipenlg/data
## Notebook Directory
- [dataaugmentation.ipynb](https://github.com/gargnishchay13/Ingredients-To-Dish/blob/main/Notebooks/dataaugmentation.ipynb)<br />
  - Used for Data Augmention<br />
- [grounded-sam.ipynb](https://github.com/gargnishchay13/Ingredients-To-Dish/blob/main/Notebooks/grounded-sam.ipynb)<br />
  - Used for Auto Annotating Dataset<br />
- [yolov8.ipnyb](https://github.com/gargnishchay13/Ingredients-To-Dish/blob/main/Notebooks/yolov8.ipynb)<br />
  - Used for training the Model<br />
- [search.ipynb](https://github.com/gargnishchay13/Ingredients-To-Dish/blob/main/Notebooks/search.ipynb)<br />
  - Used for recommending recipies<br />
  
## Final Weights
[best.pt](https://github.com/gargnishchay13/Ingredients-To-Dish/blob/main/best.pt) contains the final weights <br />


