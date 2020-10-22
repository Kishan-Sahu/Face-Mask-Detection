# Face-Mask-Detection
Develop a prototype model to detect a person is wearing a mask or not.

## Dataset
Conatain two subfolder image of faces with mask or without mask

## Face_detector
Contain pretrained model to detect the faces in the image

## Mask_detector
Contains three notebook
  ##### Face_mask_model 
    This notebook gives you a trained model as a result to detect images with mask or without mask
      
  ##### Live_stream_face_mask_detector
    Use OpenCV to take realtime video and make predictions using the trained model
  
  ##### mask_detector_on-image 
    Use OpenCV to take image as an input and make predictions on it using the trained model
