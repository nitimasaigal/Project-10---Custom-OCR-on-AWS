Custom - Object Character Recognition (AWS)

[sagemaker link](https://project10-ntbk.notebook.us-east-1.sagemaker.aws/tree)

Building a Custom OCR by combining YOLO and Tesseract, to read the specific contents of a lab report and converting it into an editable file.

Prerequisites

Before running the project, we need to ensure that we have the following dependencies installed: Python (version 3.6 or higher), yolo v3, Tesseract OCR, OpenCV.

Project Structure

The project is structured as follows:

|--Sagemaker Notebook (project10-ntbk)

| |--main.ipynb

| |--classes.txt

| |--local_image.jpg

| |--model.weights

| |--results.csv

| |--yolov3_custom.cfg

|--S3 Bucket (nitima-project10-bucket)

| |--datasets

| | |--Dataset_OCR

| | | |--images

| |--models

| | |--yolo-obj_final.weights

| | |--yolov3-custom.cfg

| |--results

| | |--results.csv

|--README.md

|--Custom OCR on AWS.pdf

After training the model, when we test and run the image, it reads all the text and creates a csv file named results.csv

The final output is as follows: 

![Screenshot 2024-10-07 115559](https://github.com/user-attachments/assets/9c537333-f355-4bf6-8816-c4a2b08c0846)


Credits/Acknowledgements

All credit goes to Shweta Mam and Twinkle Mam for this project

Contact Information

Nitima Saigal
nitimasaigal@gmail.com

Nitima Saigal
