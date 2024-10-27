# Face Emotion Detection in Manga

This project focuses on detecting facial emotions in manga-style images, categorizing them into various expressions. The dataset used includes manga facial expressions from multiple sources, as well as AI-generated images to enhance the dataset's diversity and coverage.

## Dataset Sources

The dataset consists of images collected from the following sources:

1. **Kaggle Manga Facial Expressions Dataset**
   - The initial images were sourced from the [Manga Facial Expressions Dataset on Kaggle](https://www.kaggle.com/datasets/mertkkl/manga-facial-expressions/data) created by Mert Kocakli. 
   - This dataset provides a variety of facial expressions categorized into folders like `happy`, `pleased`, `crying`, `angry`, `sad`, and `embarrassed`, representing different emotions in manga art.

2. **AI-Generated Images**
   - Additional images were generated using AI tools to expand the dataset, providing a richer set of expressions and unique styles.
   - The AI generation was done using **FLUX.1 [schnell]** by BlackForestLabs, available on Hugging Face: [FLUX.1-schnell by BlackForestLabs](https://huggingface.co/black-forest-labs/FLUX.1-schnell).
   - These AI-generated images supplement the original dataset, ensuring a more comprehensive range of expressions and improved model training results.

## Folder Structure

The dataset is organized by emotion categories, with each category containing manga images showing specific expressions. The main folders are:

- `happy`: Images representing happiness or joy.
- `pleased`: Images depicting a satisfied or pleased expression.
- `crying`: Images showing sadness or crying.
- `angry`: Images conveying anger or frustration.
- `sad`: Images depicting sadness or disappointment.
- `embarrassed`: Images representing embarrassment or shyness.

## Usage

This dataset can be used for training machine learning models in facial expression recognition, specifically targeting manga or illustrated characters. With both real and AI-generated images, the dataset offers diverse styles and expressions.

## Tools Used

1. **Kaggle Dataset**: Provided the base images with labeled expressions.
2. **FLUX.1 [schnell] by BlackForestLabs**: Used for generating additional images to enhance and diversify the dataset.

## Acknowledgments

- Thanks to Mert Kocakli for making the initial dataset available on Kaggle.
- Special thanks to BlackForestLabs for providing the FLUX.1-schnell model for AI-generated images.

This project combines existing datasets with AI tools to provide a comprehensive dataset for manga facial expression recognition.
