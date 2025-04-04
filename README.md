# Pneumonia detection using Keras model

This Application provides a Python script designed for pneumonia detection from chest X-ray images using a pre-trained Keras model. The script automates the classification of images within a designated folder and outputs a JSON file containing the results. Each entry in the JSON file includes the predicted diagnosis (e.g., "pneumonia" or "normal") and the associated confidence score, facilitating efficient and accurate evaluation of medical images.

To run the model please create a folder containing chest X-ray images you want to classify. Ensure the images are in JPEG or PNG format. 
After that please run the command "sudo docker compose up" this will create the containers and run the images in the secure enclave, finally the output will be shown in a "results.json" file in the working directory.

Example: if we run "sudo docker compose up" command, it processes all images in the ./xray_images folder and saves the classification results to ./results.json. 
