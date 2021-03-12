# Lead Country to Continent Mapping

This repo contains the results of our March 12th 2021 military trailblazer office hours call.  During the call, we discussed the following use case:  from a lead record, we want to be able to enter a Country, and from that Country, we want to automatically update a Continent field.  We followed two approaches:  1) creating a custom object to hold the country to continent mapping and 2) using a custom metadata type to do the same.

In both cases, we used a record triggered flow that triggers based on a Lead being inserted or updated, finds the appropriate continent reference record, then updates the lead.

Call recording can be found in the Office Hours group within the Military Trailblazer community.

![image](https://user-images.githubusercontent.com/1509672/110984077-a388f080-8338-11eb-806d-49a5fce45d37.png)
