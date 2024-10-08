# Real Time American Sign Language Recognition Project
Hello👋, I'm Mohamed Elsharkawy, a Data Science and AI enthusiast🥰. I recently completed a Sign Language Recognition project🧑‍💻, furthering my skills in computer vision. This project was a big step in my learning journey into AI, and I'm always seeking improvement through self-learning and making projects.⚒️

Thank you for taking the time to see about my project.❤️

## Used Technologies:

- :snake: **Python**: Programming language used for the project.
- :hourglass_flowing_sand: **Mediapipe**: Used for hand tracking and pose estimation.
- :1234: **NumPy**: Library for numerical computations in Python.
- :bar_chart: **Scikit-learn**: Machine learning library used for modeling.
- :camera: **OpenCV**: Computer vision library for image processing.
- :computer: **JupyterLab**: Interactive development environment for data science.
- :cloud: **Google Colab**: Cloud-based platform for running Jupyter notebooks.
- :pick: **Pickle**: Python module for object serialization.
- :chart_with_upwards_trend: **Streamlit**: Interactive web application framework for Python.

## Demo
![Watch Demo](media/demo.gif)

## Description
It is a sign language recognition project, used to ease the communication between normal people and deaf-mute individuals. The project focuses on recognizing American Sign Language (ASL) using hand gestures for the following signs: Goodbye, Hello, Help, Sorry, Thank you.

## ASL Signs
![Goodbye](media/Goodbye.jpg "Goodbye") | ![Hello](media/Hello.jpg "Hello")
------------------------------------|---------------------------------
**Goodbye**                         | **Hello**
**![Help](media/Help.jpg "Help")**        | **![Sorry](media/Sorry.jpg "Sorry")**
**Help**                            | **Sorry**
**![Thank you](media/Thankyou.jpg "Thank you")** | **![Balanced Dataset](media/Balanced_Data.jpg "Balanced Dataset")**
**Thank you**                       | **Balanced Dataset**

## Steps
1. **Collecting Images for the 5 Sign Languages:**
   - Since there is no given dataset, we created our own dataset.
   - Used webcam to capture images of the sign languages.
   - Extracted frames from tutorial videos to increase the dataset size and add variety.
     - [Signing Savvy](https://www.signingsavvy.com/)
     - [Sign ASL](https://www.signasl.org/)

2. **Extracting Features with Mediapipe:**
   - We used the Mediapipe module to extract features from the images.
   - This step is crucial for focusing the model on specific hand gestures.
   - Hand landmarks were detected and used as features for training.
   - The resulting dataset: extracted features and labels -> stored in `data.pickle`.

3. **Splitting Dataset:**
   - 80% of the dataset was allocated for training, and the rest for testing.
   - The dataset was balanced, ensuring each class had the same number of samples.
   - This helped avoid bias towards specific classes.

4. **Training the Model:**
   - Random Forest algorithm was used for the model.
   - Trained the model on the training data.
   - Saved the trained model in `model.pickle` for later use.

5. **Evaluation:**
   - Tested the model using the test data.
   - Calculated Confusion Matrix and other metrics.
   - Achieved an accuracy score of 98.8% for this task.
  
5. **Deployment:**
   - Used Streamlit to deploy the project as a web app using only python.
   - Host the project on Streamlit Community Cloud using [This Repository](https://github.com/mohamedelsharkawy-coder/Sign-Language-Recognition-with-Hand-Gestures-Streamlit/tree/master)
   - Web App : [Real Time ASL Recognition](https://sign-language-recognition-with-hand-gestures.streamlit.app/)
  
## 📞 Contact Information

Feel free to reach out if you have any questions, suggestions, or would like to collaborate!

- **Email:** [mohamed.k.elsharkawy@gmail.com](mailto:mohamed.k.elsharkawy@gmail.com)
- **Phone:** +20 100 462 2244
- **LinkedIn:** [Mohamed Elsharkawy's LinkedIn Profile](https://www.linkedin.com/in/mohamed-elsharkawy-6184b41a7/)
- **Kaggle:** [Mohamed Elsharkawy's Kaggle Profile](https://www.kaggle.com/mohamedelsharkawy89)

