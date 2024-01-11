Plant Disease Recognition System

-The following AI model is based on Image Recognition.


-It is used to identify the possible disease that the plant might be having.

-It takes an image of a plant's leaves and provides predictions for the plant's species and any potential diseases it may be afflicted with.

-It can facilitate farmers in accurately identifying the specific diseases affecting their crops.


The model has undergone 3 phases of development:- training, validation, and testing.

The model is developed using a very vast database:-

training: 39,889 images


validation: 9,414 images

testing: 31 images

The model is trained up to 2 epochs with 1000 steps per epoch.

Training accuracy= 85.41 %

Validation accuracy= 80.45%

The result is categorized into 38 different classes representing the state of the plant.

Technologies used: Python, Python Notebook, TensorFlow, Convolutional Neural Network, Keras, OpenCV-Python, 

Numpy, Matplotlib, Scipy, Pickle



PROBLEM SOLVED:

Despite the introduction of “Google Lens”, online image searches remain less effective, leaving farmers with the need to scour the internet for symptoms and colours of the leaves. This task becomes particularly burdensome when dealing with similar symptoms from two or more diseases. In contrast, the AI model, having been trained on a comprehensive dataset comprising roughly 50,000 images, excels in pinpointing the precise disease with enhanced accuracy.



Target Audience: 

The intended audience for the system may include:

1)Farmers and Agricultural Professionals: Those involved in agriculture who need to identify and manage diseases affecting their crops.

2)Gardeners and Horticulturists: Individuals interested in maintaining the health of their plants, flowers, or gardens.

3)Researchers and Botanists: Scientists and experts studying plant diseases, or conducting experiments related to plants.

4)Agtech Companies: Businesses working on agricultural technology solutions for plant disease management.

5)Educational Institutions: Schools, colleges, and universities teaching agriculture, horticulture, or related subjects.

6)Government Agencies: Agricultural departments and regulatory bodies responsible for plant health.

7)Environmentalists and Conservationists: Those interested in preserving and protecting plant species.

8)Anyone with an Interest in Plant Health: General users who want to diagnose and care for their plants.




Identified Classes:

The model can classify an image as one of the following 38 classes:-

Apple___Apple_scab

Apple___Black_rot

Apple___Cedar_apple_rust

Apple___healthy

Blueberry___healthy

Cherry_(including_sour)___healthy

Cherry_(including_sour)___Powdery_mildew

Corn_(maize)___Cercospora_leaf_spot Gray_leaf_spot

Corn_(maize)___Common_rust_

Corn_(maize)___healthy

Corn_(maize)___Northern_Leaf_Blight

Grape___Black_rot

Grape___Esca_(Black_Measles)

Grape___healthy

Grape___Leaf_blight_(Isariopsis_Leaf_Spot)

Orange___Haunglongbing_(Citrus_greening)

Peach___Bacterial_spot

Peach___healthy

Pepper,_bell___Bacterial_spot

Pepper,_bell___healthy

Potato___Early_blight

Potato___healthy

Potato___Late_blight

Raspberry___healthy

Soybean___healthy

Squash___Powdery_mildew

Strawberry___healthy

Strawberry___Leaf_scorch

Tomato___Bacterial_spot

Tomato___Early_blight

Tomato___healthy

Tomato___Late_blight

Tomato___Leaf_Mold

Tomato___Septoria_leaf_spot

Tomato___Spider_mites Two-spotted_spider_mite

Tomato___Target_Spot

Tomato___Tomato_mosaic_virus

Tomato___Tomato_Yellow_Leaf_Curl_Virus
