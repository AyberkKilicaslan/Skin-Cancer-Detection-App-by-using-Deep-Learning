# Skin-Cancer-Detection-App-by-using-Deep-Learning

##Melanoma Skin Cancer Detection Using Deep Learning
Melanoma is a cancer caused by pigment-containing cells called melanocytes. It is one of the most dangerous cancers. Melanoma cancer causes nearly 55,000 deaths per year, accounting for 0.7 percent of all cancer deaths.. On the other hand, recently, medical diagnostic systems with artificial intelligence support have become quite widespread. The aim of this project is to develop a mobile phone application that will help in the early diagnosis of melanoma skin cancer with the help of deep neural network models.
In the project, 4000 melanoma cancer and 4000 benign labeled skin lesion images selected from the dataset of the ISIC 2017 competition were used. After the images were passed through preprocessing processes, they were used in the training of deep neural networks. The results of different deep learning models have been compared with each other. Comparisons have been made both in terms of accuracy rates and their applicability to mobile phones. As a result of the comparisons made, the most suitable model has been determined and it has been brought to the format to be used in mobile applications.


Background Information

Melanoma is one of the most dangerous cancer types that is caused by pigment- containing cells, melanocytes. Annually almost 55,000 deaths happen which is 0.7% of all cancer deaths because of melanoma cancer (Daghrir et al., 2021).

According to the reports of American Cancer Society, about 106,110 (62,260 men, 43,850 women) new melanomas will be diagnosed in 2021. In addition, 7,180 people are expected to die of melanoma. The development of melanoma is more common as people grow older. But it also develops in younger people, including those younger than 30 years old. It is one of the most common cancers diagnosed in young adults, particularly for women. In 2020, about 2,400 cases of melanoma were estimated to be diagnosed in people aged 15 to 29.

Tissue digital image is used for detection of different types of skin cancer such as melanoma, basal cell carcinoma, etc. One of the common techniques used for this objective is epiluminescence microscopy (ELM), also known as dermoscopy (Tsong-Long Hwang, 2007). ABCD (asymmetry, border structure, color, diameter) rule is the crucial method to diagnose melanoma skin cancer. In general, lesions which include melanoma structures asymmetrically and have uneven borders. These lesions also have multicolored structure and their diameters larger than one-quarter inch.

Due to late diagnosis of melanoma cases, patient would not get proper cancer treatment in time. Therefore, easy and effective diagnosis tools, which are applicable in home environment, might help to expand the lifetime of patients.

Problem Definition

Usually, melanoma is a type of skin cancer that is detected after reaching the critical stage. It is a disease that is difficult to treat because it has a structure that spreads throughout the body. That is why the detection of melanoma should occur as early as possible. The melanoma in the dermoscopic images may not be noticed by the dermatologist. In this case, developing computer vision systems has become inevitable to use disease detection in this field. Day by day, new studies are being conducted for new automated cancer detection systems. In this project, image processing operations and deep learning techniques will be proposed to contribute to more effective diagnosis of skin cancer.



#Motivation / Related Works

Main goal of the project is to implement a dermoscopic image classification approach by applying deep learning models and image processing methods. As a result of the research conducted, it was found that there are other studies conducted on this topic. Proposed method is aimed to develop a system that gives better results by taking advantage of these studies.

Russell S. Berman et al. proposed a system that heavily relies on the processing unit for removing image occlusions and the data generation unit. In the stage of populating scarce lesion classes, or equivalently creating virtual patients with predefined types of lesions, generative adversarial networks are based on.

Adekanmi A. Adegun et al. contribute a system that includes a supervised learning method which provides an end to end and pixel by pixel classification approach using deep convolutional networks combined with softmax classifier and dice loss function.

Jinen Daghirir et al. contribute an automatic detection of melanoma lesions on skin images by using the concept of deep learning. The results indicate that deep learning methods using convolutional neural networkCNN are able to detect the melanoma lesion efficiently.

Goal / Contribution

Recently, artificial intelligence-assisted disease detection systems have become quite widespread. The aim of this project is to help the early detection of skin cancer by performing melanoma detection using deep neural network models.

In the studies to be carried out in this direction, ISIC Challenges (2016, 2017, 2018, 2020) and PH2 data that have been passed through the necessary preprocessing methods will be used during the training of deep learning models that we will use to detect melanoma.

If successful models are used in the health sector, the prevention of possible errors that may be made in cancer diagnosis will be largely provided. The diagnosis tools applicable at home would expand the lifetime of patients by taking proper cancer treatments on time.



Project Scope

Although disease detection with deep learning models is a method that has started to be applied frequently and has yielded successful results, it is not possible to access a model with one hundred percent accuracy and error-free. Diagnosis of melanoma, which has an important place in the treatment of skin cancers at the beginning, cannot be done with a hundred percent accuracy. Automated detection system that works with the highest accuracy will be created by considering the risk level.

The data that will be used for the detection of diseases will go through the stages respectively collecting, pre-processing and the cleaning from the noise, to achieve higher accuracy. The classification process required for a disease detection can be completed by different methods; making a classification based on segmented images or estimating the disease class based on the original image.

According to the proposed method, an automated melanoma detection system will be implemented. Thanks to this automation, it is expected that a patient will be classified whether the lesion is melanoma or benign according to the original lesion image of the patient.

Methodology / Tools / Libraries

In this project, it will be mentioned about the research conducted on the accuracy of deep learning models, which have become very widely used in disease detection, in the detection of melanoma cancer. Finally, a new solution will be experimented by using the methods already presented with the system obtained.

In order to develop deep learning models in a computer environment, the necessary programming languages and libraries were investigated. As a result of the research conducted, the Python programming language meets the requirements with the tools and libraries contained in it. PyTorch and Tensorflow effectively use libraries such as Keras, NumPy, Pandas, Matplotlib, OpenCV while developing a system. These tools will be used when implementing the proposed system.

In the training phase of models to be developed, a sufficient number of labeled images are needed. Different databases have been used to collect these labeled samples: ISIC Challenges, PH2. The necessary pre-processing operations will be performed on the data obtained from these databases. As initial operations, image pre-processing methods that will be used to reduce noise on images. In addition, data augmentation will be applied to balance the number of diseased (melanoma) dermoscopic images with disease-free images.

