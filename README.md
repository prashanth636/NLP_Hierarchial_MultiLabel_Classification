In the main branch there are total 3 folders 

Final Folder contains our milestone3 best models for subtask1 and subtask2a

VisualBert contains code for  ViTmodel and VisualBert

Bert_resnet50 contains the code for Bert for text model and resnet50 for Image feature Extractor

roberta 

The list of required libraries for subtask1:

torch
torch.nn
torch.utils.data
json
sklearn.metrics
tqdm
transformers

The list of required libraries for subtask2a:

torch and torchvision
transformers
datasets
Pillow (PIL)
scikit-learn
accelerate
pytorch-lightning
tqdm

In Final we have a single meme we are loading a trained model of ours 
RUNNING FRONTEND:

1. Go to Final/Single meme/frontend/
2. Run 'npm install'
3. In App.js change the backend server endpoint URL if required, by default backend runs at port 5000
4. Run 'npm start' command
5. Access the frontend at port 3000
6. Upload the meme in the webpage and also the text in that particular meme
7. Wait and see the displayed classes of the particular meme 


RUNNING BACKEND:

1. Go to  Final/Single meme/
2. Run the Flask application in backend.ipnb file 
3. Make sure the trained model is in the appropriate path
4. By default the backend app runs in port 5000
5. The backend endpoint is 'http://localhost:5000/detect_emotion'
6. You need to send the image and text parameters to this API and in return you will receive array of classes 