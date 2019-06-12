# Is It Recyclable?

Chicago provides Blue Bins for recycling, but do you know what is allowed to go in those bins? For items that are restricted, are there any alternatives to the landfill? What happens when you try to recycle something that is not recyclable?

The city of Chicago ends up diverting many of the recyclable items collected in Blue Carts to landfills because recyclable materials are "contaminated" with non-recyclable items. There is a Chicago city rule that says that one plastic bag or food item in a Blue Cart can cause all of the recyclable material in that bin to be labelled as “grossly contaminated,” which requires waste-haulers to dump it all into a landfill.

## The Challenge

Our goal is to spread awareness of how to properly recycle and dispose of waste in Chicago. This challenge compiles a recycling guide provided by the City of Chicago to help users determine what can be recycled by the city, and if something cannot be placed in the Blue Cart bins, instruct how to best manage the waste.

#### Display the Chicago Recycling Guide 

The [Chicago Recycling Guide](https://www.chicago.gov/content/dam/city/depts/streets/supp_info/RecyclingPDFdocs/AZGuide_2_1_12.pdf) is an alphabetical list of common household waste items. The list provides data as to whether the material is accepted in Chicago's Blue Cart Program, along with addition information about how to dispose of the material if it is not.

The first challenge is to display this information for the user. A JSON version of this data is available as part of this repo. 

You are encouraged to try to build a web application for this challenge. Quick start guides for Rails and Sinatra are listed below in the Resources section. The design of this is up to you, as long as it is organized in a reasonable manner.

#### Provide a dropdown for material

Using the same JSON data, create a dropdown of the materials and show the line item for the selected material.

#### Search for a material

Allow the user to search for a particular material. Keep in mind the level of specificity provided in the data. For example, a user may want to know whether "Aluminum Cans" are recyclable. Would your search return "Aluminum" or no results?

#### Add additional material

Provide the ability to add to the list. Look through resources like [Recycle by City](https://www.recyclebycity.com/chicago/guide) and [City of Chicago - What Can I Recycle?](https://www.chicago.gov/dam/city/depts/doe/general/RecyclingAndWasteMgmt_PDFs/MultiUnit/FactSheet_WhatCanIRecycle.pdf) to identify other items that are not included in the list that can be added. Make sure these items are available in the search and dropdown!

#### Link to other resources

Provide a section with links to Recycling guides and resources to help people trying to find more information. You can use the 

## Resources

* [Sinatra Docs - Getting Started](http://sinatrarb.com/intro.html)
* [Getting Started with Sinatra](https://gist.github.com/markbates/4354727)
* [Sinatra Quickstart](https://github.com/vbalazs/sinatra-quickstart)
* [RailsGuides - Getting Started](https://guides.rubyonrails.org/getting_started.html)
* [Zero-to-Sixty: Creating and Deploying a Rails App in Under an Hour](https://code.tutsplus.com/tutorials/zero-to-sixty-creating-and-deploying-a-rails-app-in-under-an-hour--net-8252)
* [City of Chicago - What Can I Recycle?](https://www.chicago.gov/dam/city/depts/doe/general/RecyclingAndWasteMgmt_PDFs/MultiUnit/FactSheet_WhatCanIRecycle.pdf)
* [Recycle by City](https://www.recyclebycity.com/chicago/guide)
* [Chicago Recycling Guide](https://www.chicago.gov/content/dam/city/depts/streets/supp_info/RecyclingPDFdocs/AZGuide_2_1_12.pdf)
* [Chicago Recycling - Printable Guide](https://www.recyclebycity.com/files/uploads/Chicago_TRP_Guide_2.pdf)
* [Recycling Quiz](https://www.recyclebycity.com/chicago/quiz/)

