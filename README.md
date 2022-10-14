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

    Pothole Detection
    
    
    Biker with no helmet
    
    
    Vehicles jumping traffic signal



### Demo video
    TBD

### The architecture
    ![Capture Traffic Photos](https://github.com/Digs1008/SLackathon-ObjectDetection/blob/main/ImageCapture.png)


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
   
   

