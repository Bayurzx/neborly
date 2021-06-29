## Project Instructions (For Student)

`I was` expected to do the following to complete this project:
# 1.1 
Students should be able to create a MongoDB database, two collections, and import raw data into the database. The MongoDB database is hosted in Azure CosmosDB.

To pass this criteria, you can provide a screenshot from the Azure portal showing the database & collections, as well as confirmation that the two pieces of sample data for advertisements (5 documents) and posts (4 documents) were imported correctly.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_1%20advert%20import-cosmos.jpg)
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_1%20posts%20import-cosmos.jpg)

# 1_2

Students are expected to deploy 7 endpoints: createAdvertisement, updateAdvertisement, getAdvertisement, getAdvertisements, and deleteAdvertisement, getPost, getPosts. There should be 7 urls with the format:

https://<STUDENT-APP-NAME>.azurewebsites.net/api/<endpoint>
To pass this criteria, show a screenshot, including URL, from the Azure portal where it is shown what endpoints are live
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_2-many-fx-url.jpg)
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_2-many-fx-url2.jpg)


# 1_3

To verify that the database is configured, the student should be able to retrieve the connection on each of their API endpoints in the server-API application.

To pass this criteria, show a screenshot, including URL, of at least the data returned from querying the getAdvertisements endpoint; other endpoints will be checked for reasonableness within the related code files.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_3%20getAdverisements-live.jpg)

# 1_4

The client-side python Flask application has the routes to obtain services created by server-side Azure Functions endpoints. The student can run the client-side application on localhost:5000 and on the home page, and should be able to view the feed of advertisements and posts.

Update the front-end code to appropriately query your published API
Provide a screenshot here of the front-end appropriately pulling up posts when you visit localhost. Note that if you have provided a screenshot or URL to a live site with the front-end later on in the assignment, that can also be used as proof here.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/1_4%20neighborlywebapp-flask-local.jpg)

# 2_1

Students should be able to create a Logic App that watches for an HTTP trigger. When the HTTP request is triggered, the student is sent an email (with Gmail) notification. The student can validate this by a screenshot of their inbox.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/2_1%20logicapp-trigger1.jpg)
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/2_1%20logicapp-trigger2.jpg)


# 2_2

The student should be able create an Event Hubs namespace and an event hub with the command line or through the portal. If successful, the student can obtain the namespace url. Add a screenshot from the portal of this being live.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/2_2%20eventhub-namespace-url.jpg)    
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/2_2%20eventhub-namespace-url2.jpg)    
    



# 2_3

The student should be able to use the endpoint connection string from the event hub to the eventHubTrigger function in the function.json file.
    ![image](https://raw.githubusercontent.com/Bayurzx/myproject/master/screenhots\2_3_event_hub_integration.jpg)    
    

# 3_1

The student should be able to use the live url from Azure App Service in their browser. The URL should be accessible to all users on the World Wide Web, or a screenshot should be provided, including the URL, of the live site.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_1%20neighborlywebapp-flask-live.jpg)    
    
# 3_2

The student can run docker build and can import their Dockerfile in the Azure Container Registry.

Provide a screenshot of the Dockerfile from Azure Container Registry as evidence.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_2%20docker_image%20ACR%20live.jpg)    
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_2%20dockerfile-gen-acr.jpg)    
    
# 3_3

The student should be able to create a cluster with the one node.

Provide a screenshot of confirmation from the terminal, or from within Azure, as evidence.
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_3%20Kubernetes%20services%20in%20Azure.jpg)    
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_3%20kube-current-contexts.jpg)    
    ![image](https://raw.githubusercontent.com/Bayurzx/neborly/master/screenhots/3_3%20kube-live-deployment.jpg)    
    


## example_images Folder ## => 👉 [example_images](https://github.com/Bayurzx/neborly/tree/master/screenhots) 👈 Folder