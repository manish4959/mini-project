Regional Detection of Traffic Congestion Using in a Large-Scale Surveillance System via Deep Residual TrafficNet


ABSTRACT

Despite the huge amount of traffic surveillance videos and images have been accumulated in the daily monitoring, deep learning approaches have been underutilized in the application of traffic intelligent management and control. Traffic images, including various illumination, weather conditions, and vast scenarios are considered and preprocessed to set up a proper training dataset. In order to detect traffic congestion, a network structure is proposed based on residual learning to be pre-trained and fine-tuned. The network is then transferred to the traffic application and retrained with self-established training dataset to generate the TrafficNet. The accuracy of TrafficNet to classify congested and uncongested road states reaches 99% for the validation dataset and 95% for the testing dataset. The proposed TrafficNet can be used by a regional detection of traffic congestion on a large-scale surveillance system. The effectiveness and efficiencies are magnificently demonstrated with quick detection in the high accuracy in the case study. The experimental trial could extend its successful application to traffic surveillance system and has potential enhancement for intelligent transport system in future.


EXISTING SYSTEM

There are existing works available in traffic detection using machine learning and deep learning approaches.

Machine learning approaches
❖ K-nearest neighbor (KNN) was commonly used to classify images. Support vector machine (SVM) was also used for classifying hyperspectral images with satisfactory results. All those traditional image processing methods were hard to use in the classification of traffic images in consideration of various scenarios and disturbances.

Deep learning approaches
❖ Hinton et al. proposed a way to perform the fast-greedy layer-wise learning of deep belief network (DBN) in an unsupervised way.
❖ Classification method shifted its research direction into the deep learning-based method and moved to artificial intelligence (AI) level.
❖ Restricted Boltzmann machine (RBM), DBN and autoencoder as the unsupervised learning approaches, are applied to study the use in medical image analysis.
❖ The ResNet architecture got the first on the ILSVRC 2015, which combined six models in different depths to compose an ensemble, achieving a top-5 validation error of 3.57%.
❖ Yu et al. successfully utilized the very deep residual networks in melanoma recognition, and get a better performance. Shen et al. proposed a module based on residual learning, which called deep cross residual module, for HEp-2 cell staining pattern classification in high accuracy. Pham et al. exploited the residual learning and applied it effectively to human action recognition. It is worth to further exploration of residual learning for traffic applications.

Disadvantages
❖ Most of existing system are considered as binary class problem.

PROBLEM IDENTIFICATION & OBJECTIVES  

PROPOSED SYSTEM
❖ To propose an intelligent based traffic detection system, which can identify dense or sparse traffic from the input image.
❖ To approach the detection as multi-class problem including fire, accident, dense and sparse traffic.
❖ The proposed approach uses CNN algorithm, which efficiently classifies the input image.
❖ The initial classification of congestion and non-congestion images are stored in the local buffer station.
❖ Each images with the detected result is added with spatial and temporal information before transmission to the regional server.
Advantages
❖ Deep learning method conquered the shortcoming of traditional machine learning algorithms
❖ A regional detection of the traffic congestion can be implemented in a large-scale surveillance system.
❖ We considered multi- class problem, in which we identify dense or sparse traffic, accident or fire.


REQUIREMENT ANALYSIS
Computer Aided learning is a rapidly growing dynamic area of research in Intelligent Traffic Systems. The recent researchers in machine learning promise the improved accuracy of perception of traffic detection. Here the computers are enabled to think by developing intelligence by learning. There are many types of Machine Learning Techniques and which are used to classify the data sets.

Functional Requirements
The proposed application should be able to identify heavy or sparse traffic. Functional requirements define a function of a system and its components. A function is described as a set of inputs, the behavior and its outputs.

Functionality
The application is developed in such a way that any future enhancement can be easily implementable. The project is developed in such a way that it requires minimal maintenance. The software used are open source and easy to install. The application developed should be easy to install and use.

Reliability
It is the maturity, fault tolerance and recoverability. The system is reliable for any number of user input and training dataset. Though we have limited the training dataset for once class to be 300.

Usability
It is easy to understand, learn and operate the software system. The user can give the image or video input and identify heavy, sparse traffic, fire accidents or accidents.

Safety
Safety-critical is issues associated with its integrity level. The computer system being used is protected by a password.
Security
It does not block the some available ports through the Windows firewall.
15

Robustness
The application is developed in such a way that any future enhancement can be easily implementable. The project is developed in such a way that it requires minimal maintenance. The software used are open source and easy to install. The application developed should be easy to install and use.

Communications
The application is developed in such a way that it is easy to identify traffic intensity and is useful in real world traffic applications.

Non Functional Requirements
Non-functional requirements determine the resources required, time interval, transaction rates, throughput and everything that deals with the performance of the system.

Maintainability
It is easy to maintain the system as it does not require any special maintenance after download. Updates are required only if notified to the user about any. Easy maintenance is one among the features that makes this proposal most usable.

Portability
The software must easily be transferred to another environment, including install ability. It is easily portable as it is implied on a regular computer. The user can access the computer from the place where the system was installed.

Performance
Less time for detection of sign once the input is arrived. Similarly, the training time also less as we given limited epoch on training.

Accuracy
The accuracy generated by our work is outperformed than any other existing models. We can recognize the traffic scene accurately.

Feasibility Study
The feasibility of the project is analyzed in this phase and business proposal is put forth with a very general plan for the project and some cost estimates. During system analysis the feasibility
study of the proposed system is to be carried out. This is to ensure that the proposed system is not a burden to the company. For feasibility analysis, some understanding of the major requirements for the system is essential.


Technical Feasibility
This study is carried out to check the technical feasibility, that is, the technical requirements of the system. Any system developed must not have a high demand on the available technical resources. This will lead to high demands on the available technical resources. This will lead to high demands being placed on the client. The developed system must have a modest requirement, as only minimal or null changes are required for implementing this system.

Economic Feasibility
This study is carried out to check the economic impact that the system will have on the organization. The amount of fund that the company can pour into the research and development of the system is limited. The expenditures must be justified. Thus the developed system as well within the budget and this was achieved because most of the technologies used are freely available. Only the customized products had to be purchased.

Social Feasibility
The aspect of study is to check the level of acceptance of the system by the user. This includes the process of training the user to use the system efficiently. The user must not feel threatened by the system, instead must accept it as a necessity. The level of acceptance by the users solely depends on the methods that are employed to educate the user about the system and to make him familiar.

Software Analysis
The project primarily focuses on sign language detection. We implemented with Python 2.6 version. The libraries required are to installed prior to execute the project. We installed CV2 for OpenCV, Keras, TesorFlow , numpy, etc.

