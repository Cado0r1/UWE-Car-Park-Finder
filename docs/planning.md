# Project Proposal

## Business Case

### Problem statement
Finding parking in Bristol can be a common issue. People might need to consult multiple sources to find car parks and the information about them. For example, you might need to search for the car park locations separately from practical details about them. My proposal addresses this in a centralised app that utilises the 'Car Parks' dataset from Open Data Bristol. You could find out practical useful information with easy filters that suit your exact need, it would allow users to quickly compare and find the car parks easily.

### Business benefits

#### 1. Time Saving
Using practical and useful filters will reduce the time users spend looking through different sources to find the needed parking information. Instead of users manually looking through external websites or the dataset itself, users will be able to quickly search for results for their specific requirements and my application will sort the information for them.

#### 2. Easier Comparison
My application will present the users results that match their selected filters. They can then compare the provided information in easy to read columns displaying things such as: Location, Capacity, Operating Times, Type of Payment. Having the information displayed in this format allows consistent easy comparison quickly.

#### 3. Centralised Information
My application pools all of the data straight from Open Data's Bristol Car Parks dataset and presents it in a useful way. This will allow users to have quick access to it without scrolling through, interpreting and navigating the raw dataset themselves.

#### 4. Imporved Used Experience
I realised that the functionality of my proposal is only as good as the way the information is laid out. I will prioritise quick filters, clearly displayed results so users can find what they need efficiently. I will also consider Accessibility such as; Text Size, Clear Labels, Colour Contrast, Ect.

#### 5. Potential Future Development
My app is only as big as the dataset allows, this means it is easily scalable for future developments. If they add more records or update it, it will directly improve the app. Additional features could include displaying location on an interactive map and google map integration directly.


### Options Considered
Google Maps: This is the most widely used competitor. Users can search, view and get directions to car parks. But Google Maps is not built for car parks and may lack information that my proposed application would offer.

Just Park: Just Park is great and finding parking with clear filters but their focus is primarily on Reserved Parking and Rented Parking spots. For the purposes of exploring options and comparing information, my application is more well suited.

### Expected Risks

#### 1. Dataset Limitations
My dataset doesn't cover every single car park in Bristol and the dataset only has 51 records. Users could fail to find the perfect car park because of this.

#### 2. Data Accuracy
The information in the dataset could be wrong or outdated. Things like operation times and payment methods might be subject to change so the information needs to be up to date for users to make a desicion.

#### 3. Dependency on the Dataset
Since we don't own the data our whole application fails if the Dataset is moved or deleted. Both of which we have no control over.

#### 4. Useability and Accesability
The data needs to be in the same format for every car park for users to accurately and quickly compare them. Additionally application support for all sorts of devices and operating systems are needed as well as proper accessibility settings.

## Project Scope
The Car Park Finder is an application that will allow users to filter through and search for car parks using the Open Data Bristol Car Park Dataset and display the information in a clear and accessible way.

1. Get the data from the dataset
2. Display the data in a clear and accesable way
3. Allow users to search and filter car park results to their needs
4. Provide users with filters such as: location, capacity, payment method and operating times
5. Display only the car parks that are defined by the filters and searchbar
6. Display the car parks in a way that can be easily compared

![Bristol Car Park Finder Context Diagram](../images/context.png)
