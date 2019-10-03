INTRODUCTION

1.1	Dermatological Abnormalities and Their Classifications
Dermatology as a medical science is the study of skin and associated structures like hair and nails. Skin is not a simple inert exterior but rather a sensory dynamic boundary which acts as a defence between oneself and the outside world. Skin serves many vital functions like controlling water, heat loss and also provides protection against infections and infestations and many other medical ailments. Hence arises a very critical need to quickly analyse and cure any dermatological abnormalities which might occur. Also it’s common knowledge that early detection in such abnormalities and early administration of corrective treatment greatly reduces the chances of serious outcomes. Initially we will be training our model to detect 4 types of abnormalities, namely, Eczema, Herpes, Melanoma, and Psoriasis.  

1.1.1	Eczema
Atopic Dermatitis or more commonly known as Eczema is an itchy inflammation of the skin. Eczema symptoms include itchy, red, and dry skin which, as stated above, are caused by inflammation. It’s most commonly found in children, although adults can get it too. It is non-contagious and can be treated with oral medications, steroid creams and light therapy.

1.1.2	Herpes
Herpes is a common virus that causes sores on your genitals and/or mouth. the body against both infectious diseases and foreign materials. Herpes is caused by two different but similar viruses: herpes simplex virus type 1 (HSV-1) and herpes simplex virus type 2 (HSV-2). Both type cause sores. Herpes can be spread from skin-to-skin contact with infected areas.

1.1.3	Melanoma
Melanoma which is also known as malignant melanoma is a type of cancer that can develop from melanocytes. Melanocytes are pigment containing cells. Melanoma typically occurs on skin and can be caused by Ultra Violet (UV) light exposure in those with low levels of skin pigment. Sometimes in Melanoma, a mole can develop with changes such as size, irregular edges, or skin breakdown. 

1.1.4	Psoriasis
Psoriasis is a condition in which skin cells build up and form scales and itchy and dry patches. It is caused by an overactive immune system. Symptoms include flaking, inflammation and discoloured patches of skin. Psoriasis treatments include steroid creams, light therapy and oral medication.

1.2	Need for Dermatological Abnormality Detection and Classification
Whenever our body is suffering from any dermatological ailment, it makes it very evident using physical characteristics in the form of inflammations, moles, etc. However, even to the trained eyes of a doctor, these physical characteristics are usually not enough to definitely characterise the underlying dermatological disorder. The recent environmental factors have just acted as catalysts to the already increasing rise in dermatological diseases. The abnormalities which we have taken into consideration in this project, usually have different stages considering how far and for how long the infection has been prevailing in the patient. The survival rate is indirectly proportional to the stage of the abnormality. In general, Stage 1 has 99.9% survival rate whereas Stage 4 has a mere 17%. Hence, the need for early and precise detection and classification is very evident as the time taken to diagnose and start the treatment of said ailment can be the difference between life and death.

1.3	Role of Neural Networks as a Solution
In recent years many new and extremely efficient neural networks and techniques associated to them have been discovered. This in turn means a potential for change in all the existing sectors in which the neural networks can be implemented. In the biomedical scenario, the change comes with the introduction of Convolutional Neural Networks (CNN) and Residual Networks (ResNet). These neural networks have been tried and tested in giving a very high level of accuracy and image classification and detection. 
By utilizing the advantages of these Neural networks, we can improve upon the hardware and overall computing software which is used in the various dermatological abnormality detection and classifications. In our Minor project, we are trying to implement and compare different models and find the best optimum combination of accuracy, speed and efficiency of the output while keeping in mind that our solution should be able to be implemented in real world and that too specifically for financially weaker hospitals.

1.4	Aim and Problem Statement
With the constant advancements being made in the various fields of technology, the field of medicine does not lag too far behind with new medical diagnosis techniques being developed every day. Furthermore, there is a rise in the number of people requiring medical attention with the continuously increasing worldwide population numbers. Even though the technologies are improving, the number of doctors still remains a little bit scarce as compared to the number of patients. The main aim of this project is to cut down on the labour time and cost required to be put down in the laboratories testing the dermatological samples and thus allow the doctors to be able to treat more patients in the same amount of time and be able to detect the problem in an early stage. With the use of cutting-edge methods and techniques we aim to collaborate to the betterment of the Dermatological Abnormality Detection and classifications and in turn help the people suffering from medical ailments.

1.5	Objective and Scope of Project
The objective of this project is to provide a method which is efficient in detection of dermatological distortion-based diseases and reduce the overall time taken by the conventional methods. As explained above, the number of different types of abnormalities, which serve an integral part in distorting the health of the skin, manifest and change when the body undergoes different types of infections, diseases and other foreign body ailments.  Through this change in the shape and size, we can help the doctors identify and shortlist the possible medical diseases a patient is currently suffering and also many a times can uniquely help in identifying the complete disease itself. 
The scope of the project follows a level-based topology with a bottom up approach. We will begin by using two very widely used neural networks – Convolutional Neural Network (CNN) and Residual Network (ResNet). Firstly, we will compute the outputs from the two neural networks in which the CNN will have pre-trained weights according to ImageNet datasets and the ResNet will keep on updating its weights per run of the algorithm. Additionally, we will try to test and implement the addition of other different neural networks as a third layer which can help improve the accuracy and better classify the results.
The next levels will consist of merging the obtained outputs and applying various mathematical algorithms to better fine tune and classify the results. The thus obtained results are evaluated based on their scores and diversified into various result classes.

BACKGROUND STUDY
 
2.1 Learning about Neural Networks 
The first and most foremost step in our background study was to learn about the neural networks themselves and learn about the various techniques and steps used to implement them and calculate the results. We started learning about what and how the various activation functions are used and the broad classification of supervised and unsupervised learning. Even though our usage was different types of CNN and RPN, in order to understand their complex networks, we had to start from the simplest of networks and understand from the most basic of perceptron. After the studies we attempted to undertake the task of understanding the CNNs and the RPN. 
 
2.2 Learning about TensorFlow 
TensorFlow is an open source software library for high performance numerical computation. Its flexible architecture allows easy deployment of computation across a variety of platforms (CPUs, GPUs, TPUs), and from desktops to clusters of servers to mobile and edge devices. Originally developed by researchers and engineers from the Google Brain team within Google’s AI organization, it comes with strong support for machine learning and deep learning and the flexible numerical computation core is used across many other scientific domains.  
TensorFlow is one of the major libraries through which the neural networks can be implemented. For us, TensorFlow will serve as the main python language library on which the whole project will be made. Hence a thorough knowledge of python and TensorFlow is necessary in order to implement our project successfully. We tried to use all the various resources available to us to learn and gather as much knowledge as possible to learn. 
 
2.3 Learning about the various Datasets and their Biological Significance 
We are working on a project which focuses on the early detection of four classes of Malaria Parasite (Plasmodium) and in order to actually implement the project efficiently, we require basic knowledge about the Blood cells, Plasmodium and its four types, its effect on human body and ways to treat this deadly disease. The project aims to target to help the overall patients and doctors alike by reducing and simplifying the task of accurately identifying the patients suffering from malaria so that their treatment can be started at very early stages which will result in high percentage of successful results and will significantly reduce the number of deaths. 
2.4 Research Papers 
To gain a basic understanding and to draw our bases we referred to research papers which gave very valuable insights into the implementation of such neural network’s projects. Each research paper carried with it a plethora of experienced insights and veteran ways of implementing a project of such magnitude. Through each paper referred (listed in references) we added a lot to our knowledge and hope to utilise the knowledge in making our project even better.  

DETAILED DESIGN 
 
4.1 Data Pre-processing 
We created our own separate dataset by collecting publicly available images of the above discussed types of dermatological disorders, namely, Eczema, Psoriasis, Melanoma and Herpes. These images were further augmented to make the project more comprehensive and accurate. In order to keep our research and proposed models as efficient and potent as possible, the dataset had been created keeping a multi-level hierarchy, in essence, each dataset was first built separately and then later combined together at a later stage so as to keep the distribution of images as uniform as possible. Initially, we had created and labelled approximately 1,200 images containing various types of dermatological disorders, however the results from these images in the initial stages of testing were not satisfactory. Hence, we went on to filter these images based on resolution and dermatological disorder content. The final filtered and potent database contained approximately half of the initial crude dataset, which was approximately 500 images. This number was arrived at after various network trainings and was decided upon the accuracy with which the images were being detected. These images were divided into 400 for training and 100 for testing. The division was done randomly so as to eliminate any form of biasness which might creep in during the creation of the dataset. The testing images are analogous to validation of the model. The said images of the dataset were labelled one by one using the open source software “LabelIMG”.  Each labelled image has a corresponding XML file which contained the corner co-ordinates of the bounding box surrounding the dermatological disorder. In order to initialise the training, these separate XML labels were converted into a combined CSV file using python scripts. 
To further avoid overfitting of our model to our specific dataset, the augmented images contain intentionally added noises and transformation (Rotational). Each such picture not only serves as a new input image but also improves the overall versatility of our model.  

4.2 Model 
While studying about and implementing our project, we came across different methods which we think can improve the computational time and accuracy. The project consisted of training and testing out different combinations (called Final Models) of three base models, namely, CNN, ResNet and RPN. Each combination was trained and tested on similar dataset and for approximately similar training time so as to keep the results bias and error free. Each of the final model was trained and tested using TensorFlow Object Detection API which is officially provided by Google. Before dwelling into the combinations, let us first look into each of the base models separately.

4.2.1 Convolutional Neural Network (CNN) 
The initializing weights of the CNN are selected based on the final weights of the model after completing the training on the ImageNet dataset. This pre-trained approach was undertaken to ensure the starting weights to be near the local maximum and help reduce training time for the main dataset. on the ImageNet dataset are used as the initialization weights of the CNN model. The convolution layers had a window size varying from 5 x 5 to 3 x 3. The image data matrix is multiplied with the weights to obtain a new matrix. Then a polling layer is added with a commonly used sliding window of 2 x 2 and sliding step of 2. The main aim of this layer is to reduce the number of parameters which are not necessary for the model. As the data goes through this layer, we will get almost half of the parameters which reduces a lot of computation and decreases the time for the training of this model.
Every convolutional layer creates a level of abstraction on the input image based on the information it received from the previous layer. The layers in the beginning of the model are generally responsible for learning edges. This is the first and foremost step in creation of feature maps. As the image get processed from the initial layers, the subsequent layers find some similarity in the edges obtained from the initial layers in the form of patterns. This serves as a base for finding and recognising more complex shapes and so forth. The end result of all the processing is a feature map which contains the spatial dimensions which are significantly smaller than the original image, but boast greater depth. These attributes of the feature map are obtained due to the various pooling layers and vast number of filters respectively. Through the depth of the feature map, all the information of the original input image is captured while maintaining the locational co-ordinates of the features it has encoded with respect to the input image. A complete example of a sample CNN is depicted in Fig. 4.1.

4.2.2 Region Proposal Network (RPN)
RPN serves a vital part in increasing the efficiency and reducing the computational time of this proposed model. The purpose of RPN is to provide the CNN multiple proposals which might be potential objects. RPN does so by identifying and taking anchors of an input image and outputs a set of good proposals for possible objects present in the input image. Every anchor produced by the RPN has 2 attributes associated with it. The first being the probability value that the output anchor is an object and the second being the bounding box regression for adjusting the output anchor to optimally fit the predicted object in the input image. RPN does not classify any potential object but rather just serves as a guiding tool for the underlying object detecting model (in this case a CNN). Through this proposed model, the output anchors of the RPN will further undergo a filtration based on their probability attribute and he corresponding bounding box regression co-ordinates into the CNN layer. The input to the RPN will be the feature maps obtained from CNN's initial layers.

4.2.3 Region of Interest Pooling (ROI)
The next step in the proposed models is to classify the bounding boxes of the various object proposals obtained from our RPN-CNN model. To solve this, the already obtained feature map is reused to extract fixed sized feature maps for every potential object proposal using region of interest pooling. These new feature maps obtained are then used to assign a probability score for each possible class the image can be. The class with the highest probability is selected as the output class for the input image.

4.2.4 Residual Network (ResNet) 
A Residual Network (ResNet) is an artificial neural network (ANN) of a kind that builds on constructs known from pyramidal cells in the cerebral cortex. Residual Networks do this by skipping connections or using “short-cuts” to jump over some layers. This network brings in the much needed concept of residual learning into our final models. Residual learning helps reduce the need of LSTMs in models relating to biomedical implementations which greatly reduce computational load on the base hardware. Deep convolutional neural networks have led to a series of breakthroughs for image classification. Many other visual recognition tasks have also greatly benefited from very deep models. So, over the years there is a trend to go deeper, to solve more complex tasks and to also increase/improve the classification/recognition accuracy. But, as we go deeper, the training of neural network becomes difficult and also the accuracy starts saturating and then degrades also. Residual Learning tries to solve both these problems. In general, in a deep convolutional neural network, several layers are stacked and are trained to the task at hand. The network learns several low/mid/high level features at the end of its layers. In residual learning, instead of trying to learn some features, we try to learn some residual. Residual can be simply understood as subtraction of feature learned from input of that layer. ResNet does this using shortcut connections (directly connecting input of nth layer to some (n + x) th layer. It has proved that training this form of networks is easier than training simple deep convolutional neural networks and also the problem of degrading accuracy is resolved. This is the fundamental concept of ResNet. In our model ResNet is generally used as the last block of the model so as to see the benefits of using ResNet and also identifying which combination of networks gives the best results for our desired dataset. 
 
IMPLEMENTATION  

After installing all the required software like Anaconda Navigator, TensorFlow, Python 3.6 and its libraries we moved on to collect images and create our dataset. Our first dataset had a total of approximately 1,200 images covering all the four classes of dermatological disorders, namely, Eczema, Psoriasis, Melanoma and Herpes. This crude dataset was later refined and filtered down to approximately 500 images. As discussed in previous sections, the filtration of these images was based on resolution and dermatological disorder content. This number was arrived at after various network trainings and was decided upon the accuracy with which the images were being detected. These images were divided into 400 for training and 100 for testing. The division was done randomly so as to eliminate any form of biasness which might creep in during the creation of the dataset. The testing images are analogous to validation of the model. In order to do the above training, we had to first create a virtual environment in which our python will run. After the creation of the environment, we went on to install TensorFlow followed by the various different libraries which we required to complete our project. These included, but were not limited to, pillow, lxml, cython, jupyter, matplotlib, pandas, OpenCV-python. In order to run the python in our environment we had to define the PYTHONPATH variable and incorporate it with our operating system’s PATH variable.  

After the initial configurations, we went on ahead to create our label map which would serve as the guiding path to our network in detecting the various objects. Label map contains a list of the various classes our model can/needs to detect in a predefined syntax. For TensorFlow to train on what the objects are we had to label each picture showing where the objects are located. As mentioned before, this was done using a software LabelImg which is a great open source image labelling tool which converts the objects in these pictures to an XML file. These XML files contain the boundaries of the objects in the image. Now in order to create TensorFlow records we need to convert these XML files into a CSV file using python scripts. 
After labelling these images we activated our virtual environment using command prompt. Then this CSV file is imported using command prompt and we had trained our network many times on 2 different laptops, having NVIDIA 750 and NVIDIA 1050 graphics card respectively. By also incorporating the 750 series graphics card, it provided us with a holistic approach by covering how the network training and implementation would work when run on a low powered laptop (hardware wise). The 1050 graphics card was our opus magnum and was the main hardware which completed and tested our work. Any neural network’s training process requires a lot of computational power hence it takes several hours to train our model. We had completed various training sessions on both these laptops ranging from 1 hour 35 minutes to 21 hours. These practices assured us that our project was on the right path and gave us the insights required to tweak our methods and datasets to achieve greater results.      
After the most important and computationally expensive training process ends, we ran our test images. These images were passed through our model and we received the outputs which contained bounding boxes around the objects which contained the probability of that particular image belonging to the respective class. This testing was possible by freezing the weights of our network after training and this was done by extracting the inference graph. Inference graph is basically just a collection of all the weights of each node in our network. The outputs were generated with the help of Softmax Layer. This SoftMax is nothing but a probability Distribution which tells us about the probability that this image belongs to this class. The comparisons between the Final models were done using TensorBoard, output accuracy and computational time.

CONCLUSION 
 
Faster R-CNN is one of the models that proved that it is possible to solve complex deep learning problems with the same principles that showed such amazing results at the start of this new deep learning revolution. 
New models are currently being built, not only for object detection, but for various other technical fields, that are based on this original model. Some borrow the RPN, some borrow the R-CNN, others just build on top of both. This is why it is important to fully understand what this model is actually doing so we are better prepared to tackle future problems. 
This project uses Convolutional Neural Network to identify the images of the blood cell of the patients who are suffering from Malaria. These images contain four different type of Malaria Parasite as mentioned above. By just looking at the image this model can automatically detect the malaria parasite and output the bounding box across the plasmodium parasite which can be really helpful in early detection of Malaria. The time taken by the doctors for analysing the sample can be cut down and the treatment process can be started immediately which can save the life of such people who lose this fight by fractions of second. 
Finally, we tested this model on some random images from Google and this model was pretty accurate in separating the images which contain Malaria Parasite from the healthier ones. Then we made a video of various images of blood cell collected by the blood samples from the patients suffering from malaria and as soon as the video is given as the input to this model it clearly creates bounding boxes across all the Malaria parasites as the video progresses. It was able to identify all four different types of parasite and nearly all the parasites were detected by the model in the input video. 
 
FUTURE SCOPE 

Even though we accomplished our aims with which we had set out to complete our Minor, along the journey of working on this topic and gaining lots of new knowledge, we have arrived at the conclusion that our project plays a pivotal role in the rising trend of combining engineering and medical fields together. Further serving our goal to empower the financially low funded hospitals, our project can be worked upon to run on different neural networks like the MobileSSD networks which can be run on smaller devices like a RasberryPi, mobiles, etc.  
Furthermore, our project work successfully lays down path for future incorporation of other pathogens which will provide today’s doctors more efficient and time saving methods to diagnose the various lifethreatening diseases like anaemia, dengue, etc. Which are caused by different pathogens. Another future application of our model can be the detection of those diseases like Leukaemia, leishmania, DIC (Disseminated Intravascular Coagulation), Filariasis, etc in which the coagulation of blood cells takes place. 
Our model can be further configured to provide a count of the various kinds of cells and parasites detected in the given sample image. This will, in turn, speed up the diagnosis process even further. We can also tweak our project to create a more user-friendly UI making it easy to use for everyone and making the facilities more accessible for everyone.
