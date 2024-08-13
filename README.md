# Pneumonia detection using Keras model

This Application provides a Python script designed for pneumonia detection from chest X-ray images using a pre-trained Keras model. The script automates the classification of images within a designated folder and outputs a JSON file containing the results. Each entry in the JSON file includes the predicted diagnosis (e.g., "pneumonia" or "normal") and the associated confidence score, facilitating efficient and accurate evaluation of medical images.

The requirements are specified in the file "requirements.txr" file. Please install them through the "pip install -r requirements.txt" command.

To run the model please create a folder containing chest X-ray images you want to classify. Ensure the images are in JPEG or PNG format. 
After that please run the "python image_classifier.py <input_folder> <output_file>" command. Please replace the <input_folder> by the path of input folder in which the images are present and <output_file> by the output file you want to see in your current directory.

Example: if we run "python script.py ./xray_images ./results.json" command, it processes all images in the ./xray_images folder and saves the classification results to ./results.json. 
