# Fashion-Image-Description-Using-AI
Designed two models where the first one will take any fashion image URL and generate an AI based description and the second model will predict the Material, pattern and neckline attribute for the same image URL input.

# Generate descriptions using AI:
Performed Transfer learning using ResNet50 model to generate prediction array of the image.
Text Preprocessing is done on the descriptions and and then vocabulary is created to store them using count of words tecqnique.
Finally two deep learning models were created, one takes description of images in count of words technique and another taking image features generated using Resnet model,as input
and then concatnated these two to main LSTM model.



