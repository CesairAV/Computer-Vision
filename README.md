a.Link to the dataset:
https://drive.google.com/drive/folders/1_W_8ZT2yGibD4CpH-KUCohD6RIFu9Ttm?usp=sharing


b.I used the extension of google chrome 'Download All Images' to get the dataset.


c.At first after I downloaded the images I deleted all the images whose storage size was less 
than 11kb as those photos contain some kind of symbol or poor quality images. Then I remove all the 
images with extensions other than ['jpeg','jpg','bmp','png'] . 
I had to divide each image by 255 so that the scaling remain between 0 and 1 rather than 
0 and 255 which helps the deep learning model to produce better results.
Then I divided the complete dataset into batches 
on ploting these batches I got to know that which number was alooted to which gender. I recently got to know that 
now we have to use 'keras.model' instead of 'tensorflow.keras.model'.


d. To run your model you should have :
tensorflow, open-cv ,matplotlib ,imghdr ,numpy and keras and to do this run the line below 
in you device:
'! pip install tensorflow opencv-python matplotlib numpy'


e.
<img width="1440" alt="Screenshot 2024-05-23 at 19 19 25" src="https://github.com/CesairAV/Computer-Vision/assets/157805307/33fd96d8-b8d2-4683-b83a-bd7afb440605">
<img width="1440" alt="Screenshot 2024-05-23 at 19 19 17" src="https://github.com/CesairAV/Computer-Vision/assets/157805307/fb13d2eb-1e2d-41bf-9e81-35bab7d355eb">
<img width="1440" alt="Screenshot 2024-05-23 at 19 19 45" src="https://github.com/CesairAV/Computer-Vision/assets/157805307/61328151-d7a6-460d-8e28-5b59da51fed1">
<img width="1440" alt="Screenshot 2024-05-23 at 19 19 37" src="https://github.com/CesairAV/Computer-Vision/assets/157805307/0628de07-4c92-45c5-8689-7b2348f9c431">
<img width="1440" alt="Screenshot 2024-05-23 at 19 19 31" src="https://github.com/CesairAV/Computer-Vision/assets/157805307/a00184a3-0420-4115-b72d-cd419038b012">
