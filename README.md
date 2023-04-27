
This notebook is the 3rd step in our pipeline.

1. The **first notebook** extracts image descriptions from images using Visual Question Answering (VQA).
2. The **second notebook** takes those descriptions together with the respective post titles and roasts, and fine-tunes GPT-2-XL, a model with 1.5b parameters.
3. The **third notebook**:
    - Uses the same VQA model to extract image descriptions from some new image (that was not in the training set).
    - Loads the fine-tuned GPT-2-XL model and feeds it the image description together with some text created by the user (i.e., "roast me, you a%$holes!").
    - Generates 8 new roasts!

This project demonstrates a complete pipeline for generating humorous and personalized roasts based on image and text inputs. (chatgpt added this line itself)
