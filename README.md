# project

# Face Recognition


Face recognition is a method of identifying or verifying the identity of an individual using their face. Face recognition systems can be used to identify people in photos, video, or in real-time.



# NTRODUCTION
Face recognition systems are part of facial image processing applications and their significance as a research area are increasing recently. They use biometric information of humans and  are applicable easily instead of fingerprint



# DESIGN 
various methods and combination of these methods can be applied in  development  of  a  new  face  recognition  system.




	
# Algorithm
The most evident face features were used in the beginning of face recognition. It was a sensible approach to mimic human face recognition ability. There was an effort to try to measure the importance of certain intuitive features (mouth, eyes, cheeks) and geometric measures (between-eye distance, width-length ratio). Nowadays is still an relevant issue, mostly because discarding certain facial features or parts of a face can lead to a better performance .




# The problem
improved the performance of automated face recognition algorithms on a variety of challenging face recognition tasks. Because humans currently perform face recognition tasks in most real-world security situations, it is unclear whether the use of algorithms improves security or puts it at greater risk.








# Emotion Detection Use Cases: TSA Screening, Audience Engagement, And More

Understanding contextual emotion has widespread consequences for society and business. In the public sphere, governmental organizations could make good use of the ability to detect emotions like guilt, fear, and uncertainty. It’s not hard to imagine the TSA auto-scanning airline passengers for signs of terrorism, and in the process making the world a safer place.



Companies have also been taking advantage of emotion recognition to drive business outcomes. For the upcoming release of Toy Story 5, Disney plans to use facial recognition to judge the emotional responses of the audience. Apple even released a new feature on the iPhone X called Animoji, where you can get a computer simulated emoji to mimic your facial expressions. It’s not so far off to assume they’ll use those capabilities in other applications soon.

This is all actionable information that organizations and businesses can use to understand their customers and create products that people like. But it’s not exactly a piece of cake to get a product like this working in practice.


# Data
This project is one of the T5 Data Science BootCamp requirements. Kaggle website https://www.kaggle.com/gauravsharma99/facial-emotion-recognition/data 


# DESIGN OF A FACE RECOGNITION SYSTEM
A throughout survey has revealed that various methods and combination of these methods can be  applied  in  development  of  a  new  face  recognition  system.  Among  the  many  possible approaches,  we  have  decided  to  use  a  combination  of  knowledge-based  methods  for  face detection part  and  neural  network  approach for  face recognition part.  The  main  reason  in  this selection  is  their  smooth  applicability  and  reliability  issues.  Our  face  recognition  system approach is given in Figure

 
	


# Model Architecture
We all know that training a Convolution Neural Network(CNN) from scratch takes a lot of data and also compute power. So we instead use transfer learning, where a model trained on similar data is fine-tuned as per our requirement. The Visual Geometry Group (VGG) at Oxford has built three models — VGG-16, ResNet-50, and SeNet-50 trained for face recognition as well as for face classification. I have used the VGG-16 model as it is a smaller model and the prediction in real-time can work on my local system without GPU.









 

Running the example loads the model and prints the shape of the input and output tensors.

