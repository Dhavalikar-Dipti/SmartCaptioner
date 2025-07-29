# SmartCaptioner

**Smart Captioner** is an AI-powered image caption generator that analyzes uploaded images and suggests the most relevant and engaging Social media-style captions. The system uses the CLIP model to understand image content and predict its category from 16 possible types, then returns 5 suitable captions.

## Features

- Upload an image and get **5 creative, category-based captions**
- Uses **OpenAI's CLIP** model for image classification
- Supports **16 unique image categories**
- Clean and user-friendly **Django web interface**
- Fully functional **Android app built using Kodular**

AI Model - CLIP
The app uses CLIP (Contrastive Language–Image Pretraining) from OpenAI to classify the uploaded image into one of the 16 categories. Based on the predicted category, the app randomly selects 5 captions from a curated text file containing category-specific captions.

Future Enhancements
Add multilingual caption support

Let users vote or like captions

Fine-tune CLIP or use other vision-language models for better accuracy

Add user profiles to save captions or recent uploads
