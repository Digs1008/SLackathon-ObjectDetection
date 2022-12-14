# Road Safety and Management

## Short description

### What's the problem ?

In this project, we would be dealing with multiple problems related to road maintenance, traffic management and safety. There are close to 6000 deaths in India due to accidents caused by potholes. Also due to potholes, there is huge traffic even on a multi lane road adding 10 to 30 minutes in commute time based on factors like weather, peak office time etc. BMC pays 18,000 ruppes on average per pothole. It has spent 15 Cr in last 2 years but the state of the road doesn't reflect the cost.

Another aspect of this problem is to understand what causes so many potholes. Is the vendor selected to fix the pothole has good history of work ? Are the charges reportd to  fix a pothole nominal ? How lonng it takes to for a fixed pothole to go back to earlier state ?

Another such category is "bikers not wearing helment" and death count in such accidents is 40,000 in India !!! There is a fine of 500 Rs as well for bikers not wearing helmet. On an averager, 1000 bikers get fined each month resulting in 5 Lakh rupees. But again this number is not inline with actual violations.

The next category of road safety is finding the vehicles which are not adhering to traffic signals (jump the signal when it's red etc.)


### How can technology help?

We can build a mobile application that would have <i>CNN based deep learning model</i> as it's core component. This model would use <b>object detection techniques</b> and create bounding boxes on the objects identified such as people, potholes, vehicles etc.

The next Qn is where does the application fetches such images from ? For this part we would rely on cameras installed at various traffic signals by local governing body. The obvious limititaion here is not every traffic signal has camera and installing it would be a much bigger cost.
To address this, we can rely on the fact that most people have a smartphone with good camera. The porposla here is to allow individuals to click photo of potholes or bikers with no helmet etc and upload it to the application.

The next Qn could be why would individual take that effoert ? 
Well, given this whole process is going to improve the overall state of traffic and road, it would effectively benefit every individual commuter. But we would further add some reward system wherein individual would get points for each unreported pothole or traffic violation.


### The idea

The proposal here is to build an application that can help with multiple usecases we discussed under problem section. 
The application should have access to the traffic camera feed. It will have a UI interface wherein the users having smartphone can upload images. This application should be integrated with the systems of local governing body to perform various actions as described below :

1. Signal cameras feed could be primarily used to find traffic violation .e.g over speeding, signal breaking, no helmet while riding bike etc.

2. For Pothole detection we rely on people using the app and uploading the photos. Some drones could be further deployed which can click photos of road in 
   night (least traffic so clear visible roads).
   
3. A new case would be created everytime a new pothole is detected. There would be whole lot of data that would be captured from creation to closure of the    case such as Time Taken, Rupess Spent, Number of Labors, Actual Start of the work, vendor, No of accidents that happen due to that pothole etc. This    
   data would further be used to build a new ML model which would help with roadmap items such as vendor selection, special handling of certain roads,    
   maintenance cost prediction etc.
   
4.  The application would also deduce some more data such as  vehicle volume/flow over day , type of vehicles (heavy, medium, small etc), traffic jam points etc based on the traffic camera feed. This data could be further used to build a new model that can help with prediction of potential flyover points. The ML model should also be able to establish relation between the  wear and tear of the road due to above mentiond data points  and predict road maintenance schedule as well.  


<img width="612" alt="ImageCapture" src="https://user-images.githubusercontent.com/37891634/195841215-59c8d4e3-833e-447c-a153-632d859c4b9d.png">


    Pothole Detection
   <img width="1102" alt="PotHole-Detection" src="https://user-images.githubusercontent.com/37891634/195845162-3796af74-b1bb-4109-971e-06ecd1adfafd.png">
 
    
    Biker with no helmet
<img width="1083" alt="Traffic-Violation" src="https://user-images.githubusercontent.com/37891634/195848084-df206e37-2b2f-422d-83c4-a4dfead88fe8.png">
    
    
    Vehicles jumping traffic signal

<img width="1071" alt="violation-2" src="https://user-images.githubusercontent.com/37891634/195848972-088389d5-59e4-4598-b611-032003fe11e4.png">


### Demo video
    TBD

### The architecture

Process wise flow is already covered above.

### Dataset

https://www.kaggle.com/datasets/chitholian/annotated-potholes-dataset 

### Project roadmap

The application would  evolve to help with below more items :

   . Classify potholes under variou categories such as small, large, medium based on the size. Also classify them based on the impact as "life 
   threatening", "huge-traffic", "medium-traffic" etc. This combined together would help in prioritizing the fixing of potholes as all can't be done in one 
   go.
   
   . Vendor Selection for road maintenance based on their performance of fixing the potholes reported by the application
   
   . Prediction of traffic volume on various roads and it's impact on road condition. This in turn can help with identification of spots with potential   
   flyover construction.
   
   . Predicting road maintenance schedule that could minimise pothole creation on road.
   
   . Identification of the places where more traffic violation incident takes place. The local authority could deploy more traffic police in such areas. So 
   it helps with  better utilization of man-force that traffic department has. 
   
   

