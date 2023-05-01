# Image_Classifiermodel
It is the model for image data set 
1.Need to open google colab and upload the dataset file into your drive by clicking on upload files in the collab.
2.for unzipping the files i have used this code
from google.colab import drive
drive.mount('/content/drive')
import zipfile
zip_ref = zipfile.ZipFile("/content/drive/MyDrive/image_dataset.zip", 'r')
zip_ref.extractall("/content/drive/MyDrive/dataset")
zip_ref.close()
3.!pip install livelossplot
and also need to install livelossplot by using pip command
4.And also need to  click on runtime by runall
