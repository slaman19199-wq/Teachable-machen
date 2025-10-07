
# Teachable-machen
Machine learning was used to teach a computer how to differentiate between two different classes of images by training an AI model based on smart learning.
First, we log into Teachable Machine and select the project category. We then determine the number of categories we want to use and generate a variety of images for each category.
Once finished, we click the "Train Model" button to begin the training process. After training the fabric test model, we add a new image it has never seen before and observe how it classifies it.
When the model is working properly, we move to the export step, where we select the TensorFlow option and specify Keras as the save format.
We then export the model and save it to the project files. Finally, we copy the generated code for later application in projects or applications.
First, download the Visual Studio Code editor, create a new folder, and add a .py file to write Python code.
Next, paste the code we copied from Teachable Machine into the file.
Move on to insert the required files:
• Copy the path to the Keras model file and prefix it with the letter r to convert it to a raw string.
• Repeat the same step with the image file we want to test, as well as the labels file.

After ensuring the paths are correct, go to the bottom-left corner of the Visual Studio Code window and click "Select Python Interpreter." Then, choose the default environment or the environment we created previously to work on the project.
Finally, we execute the code to preview the model results and test the classification accuracy.
First, we download and install Anaconda on the machine. Then, we create a new virtual environment and select Python 3.10.18. After creating the environment, we click "Open Terminal" to open the terminal within Anaconda. Then, we begin installing the required libraries one by one. We type the command "pip install opencv-python" and wait for the installation to complete. Then, we type the second command "pip install pillow" and wait for it to complete. After that, we type the final command "pip install tensorflow==2.12.1". After completing the download of these packages, the environment is ready to use and work on the project.
"C:\Users\AL-anoud\Documents\sun1.jpg"
"C:\Users\AL-anoud\Documents\code.jpg"
