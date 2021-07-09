# Personal-Safety-Equipment-Detection-System-wobot
Hardhat/ head detection dataset is available here: Dataset Link  Dataset annotation format: Pascal VOC (XMLs)


 Stage 1 – Evaluation: Deep Learning

    Train the deep learning model on the given dataset.  
    We expect a hardhat/head detector. However, there is no restriction on getting creative.  
    Once you train the model, write an inference script, and process the provided YouTube video with the detections.  
    The processed video should contain bounding boxes detecting head or hardhat with varying color as per the class and confidence score in percentage. 
    Write a document and explain in detail about what is the approach and speak about why you chose the same. Be precise, concise, and write in points and add images/illustrations if required.  
    Submit: 
        The processed video for evaluation. 
        The document in the form of a PDF.

6. Stage 2 – Evaluation: Find the Color

    For every detected hardhat in the Stage 1 problem, the bounding box color should match (or at least closely resemble) the color of the hardhat itself.  
    Do the above step on a frame-by-frame basis. So, the detection bounding box color changes dynamically based on the hardhat’s color for each frame, each detection. 
    Add the details to the stage 1 document and explain in detail about what is the approach and speak about why you chose the same. Be precise, concise, and write in points and add images/illustrations if required. 
    Submit: 
        The processed video for evaluation. 
        The document in the form of a PDF. 

7. Stage 3 – Evaluation: mAP

    After stage 1, use the same model to run inference on the test set of 250 images.  
    Write down the predictions in the form of Pascal VOC format. Sample format: Sample XML Format.
    Please ensure that the filenames of the XML files should match that of the images. Otherwise, we will be unable to grade your assignment.  
    Submit:
        The zip file containing the resulting XML files of the test set
