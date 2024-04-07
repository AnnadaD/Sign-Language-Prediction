# Sign-Language-Prediction
Develop a real-time sign language detection system using image processing.
**MOTIVATION**
The motivation is to enhance inclusivity for individuals with hearing impairments. By developing
a sign language detection system, we aim to facilitate effective communication, promote social
integration, and provide equal opportunities. Leveraging technology, especially in the realms of
computer vision and machine learning, allows us to bridge communication gaps and foster a
more inclusive society, ensuring everyone can participate fully in various aspects of life.

**PROBLEM STATEMENT**
Develop a real-time sign language detection system using image processing. Challenges include
variable gestures, real-time processing, background noise, limited datasets, and user
adaptability.

Achieve accurate and robust gesture recognition in real-time, ensuring adaptability, user-
friendliness, and scalability for diverse users and environments.

Enable seamless communication for individuals with hearing impairments, breaking down
barriers and fostering inclusivity in education, employment, and social interactions.

**LEARNING OBJECTIVE**
1. Skill Enhancement: Developing expertise in image processing, machine learning, and
real-time systems will enhance technical skills, making the individual more proficient in these
domains.
2. Problem-Solving: Addressing challenges related to real-time gesture recognition fosters
strong problem-solving abilities, a crucial skill in any technical field.
3. Social Impact: Projects with a social impact, like aiding communication for people with
hearing impairments, can provide a sense of fulfillment and purpose, driving motivation and
dedication.
4. Teamwork and Collaboration: Collaborating on a multidisciplinary project hones
teamwork and collaboration skills, essential in professional environments.

**Abstract**
Sign language recognition has gained significance as a means of enhancing communication for
individuals with hearing impairments. This report presents a comprehensive study on the
development of a sign language recognition system. The system is designed to capture,
preprocess, and interpret sign language gestures using machine learning and image processing
techniques. The primary components of the system include image capture, preprocessing, and
model-based recognition. The preprocessing stage involves operations such as cropping,
Gaussian blur, binary thresholding, and edge detection, followed by a deep neural network
model trained on sign language data. The report details the implementation, challenges, and
fine-tuning of these components.
The study demonstrates the application of image processing techniques, including gray-level
slicing and edge detection. The deep learning model leverages convolutional neural networks
(CNNs) to recognize sign language gestures from pre-processed images. Experimental results
show promising accuracy and highlight the importance of robust preprocessing for model
performance.
The report concludes by discussing the potential for real-world applications of the sign language
recognition system, such as facilitating communication for the hearing-impaired community
and promoting accessibility. Future work includes expanding the dataset, optimizing model
architecture, and exploring real-time recognition capabilities. Overall, this study contributes to
the advancement of assistive technologies for the deaf and hearing-impaired population.
Workflow:

1. Data Collection : Collect data from various sources and load it. Make a proper train data.
2. Pre-processing :
2.1 Extract relevant features from gestures.
2.2 Use contrast adaptive histogram equalisation
2.3 Gamma correction
2.4 Scaling to desired range
2.5 Gaussian Filtering
2.6 Canny Edge detection
2.7 Normalize images
2.8 Adaptive thresholding
3. Model Training: Train a machine learning CNN model, focusing on accuracy.
4. Real-time Processing: Develop real-time processing for gesture recognition.
5. User Interface: Build a user-friendly interface for gesture input and display.
BLOCK DIAGRAM
<img width="567" alt="Screenshot 2024-04-07 at 9 27 28 PM" src="https://github.com/AnnadaD/Sign-Language-Prediction/assets/94922120/be5daabc-c4e8-4622-ba99-46c8a18d97e3">

**TECHNOLOGIES USED:**
1. OpenCV
2. CNN ( Convolutional Neural Network )

HARDWARE REQUIREMENTS:
1. A device with webcam.
