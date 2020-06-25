# Route finding app with Azure
A route finding app built with Microsoft Azure maps taking hazards into account.

## Demo 
![Route finder app demo](https://github.com/ayeshaf9/route-finder-azure/blob/master/routeFinderDemo.gif)

## Setup

1. Create a [Microsoft Azure](https://azure.microsoft.com/en-us/) account and then go to the [Azure portal](https://portal.azure.com/#home).


2. Click **Create a resource** > Search and select an **Azure Maps** instance > Click **Create**.

![Create Azure Map resource](https://github.com/ayeshaf9/route-finder-azure/blob/master/createResource.gif)

3. Choose Concierge Subscription and sandbox resource group beginning with learn-.

4. Name the resource `RouteFinder` or anything similar and leaving pricing tier as it is > Click **Create**

5. Once the resource is deployed, click **Go to resource** > Settings > Authentication > Copy the Primary Key and plug it into the `route_finder.html` file.

6. Launch the app on Live server.

## Features

The app finds routes for 3 types of vehicles including a bicycle, a car, and a truck. The truck has an additional load variable which enables the routes to have a feature to select routes based on hazardous material classification for the trucks. The app has been edited to find routes in cities in the United Arab Emirates.

## Learn more 

[Create your first route find app with Azure Maps](https://docs.microsoft.com/en-us/learn/modules/create-your-first-app-with-azure-maps/)

[Azure Docs for Azure maps](https://github.com/MicrosoftDocs/azure-docs/tree/master/articles/azure-maps)
