# CropAI
Crop disease prediction using deep learning

Use Case:
Farmers lack an efficient way of easily detecting crop diseases which leads them to lose their entire produce. This affects close to 40% of Global crop production and costs the global economy around $220 billion. (Source: United Nations) Expensive agronomist are required to travel long distances to access farmers crop fields to diagnose simple diseases and limited agricultural personnel to recommend pesticides to treat their crops
Despite the various technological advancements there is no feasible solution that has been implemented at a large scale to combat this problem which will only become larger as food production increases due to increase in population.

Solution:
An application that uses artificial intelligence to detect crop diseases, provide the appropriate disease diagnostic to farmers.
Recommendation to farmers on the appropriate pesticide (organic preferred) to treat the diseases.
Providing farmers, a simple platform with means of purchasing the pesticides and having it delivered to their crop fields.
An end to end solution to combat decrease in global crop production and global economy amidst growing food production demand.

Data Source:https://data.mendeley.com/datasets/tywbtsjrjv

Solution Methodology:
Farmers download the application and register on the application integrated with local payment platform
Using their phones farmers open the Oracle developed application and take pictures of leaves of the diseased crops from within the application
Farmers then submit the image to the A.I application engine which runs in the background 
The crop disease is then identified with state of the art machine learning algorithms using OCI-Data Science in the backend
The application then intelligently recommends the appropriate pesticide for the plant and provides a link to the nearest agrovet for farmers to order the agrovet
The application then logs the data for analysis to identify if there is a region-wise disease outbreak and alerts authorities .
Thus, this end to end efficient solution when implemented, will increase food production capabilities, improve global economy and provide a hassle free experience to the farmer.


Possible Future Work:
Drones to survey the agricultural field and capture images of plants with diseases
Images are continuously streamed to a storage and an AI model analyzes the image to find the right pesticide.
Another set of drones spray the right amount of pesticide to the right crop by considering the wind speeds.



