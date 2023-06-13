# SnT_Hackathon_Illuminati
For Solve For IITK problem statement, we have implemented an application using `panel` library in python in which user can upload a pdf and then receive answers to his questions. For generating answers, we have used the model `deepset/roberta-base-squad2` which is a part of Hugging Face models and pre-trained on the  SQuAD2.0 dataset. The model has been implemented using the `transformers` library of Hugging Face. For input, currently we have only implemented for pdfs but there is an OCR feature too which lets user get answers on textual images in pdfs. The OCR feature is implemented using `easyocr` library in python.

To run the model, **open the .ipynb file** in google colab and run it with **GPU runtime type**. The file has to be uploaded into the app from the user's local device. Due to time and logistics constraints, we could not host the app on Hugging Face as we had intended before. 


Below we have shown some sample questions and answers that the model has returnd based on the sample pdf.
![Test](https://github.com/rudradeep22/SnT_Hackathon_Illuminati/assets/121369407/8466b7bc-2046-43c7-8ac5-3ba0942816a1)
