# Hotel-Case-Study

## Real Case Study, with Real Data

To expand any business, it is necessary to gain new customers. Hotel H, located in Lisbon, Portugal, like any other industry, wants to expand its business and make more profit by attracting new clients. The key to that is to analyse and study the hotel’s current clients and identify the distinct groups of customers, so that market strategies can be shaped and changed considering the diverse groups’ interests and responses to campaigns.

With that in mind, hotel H had already developed a marketing segmentation. However, this original solution can be improved by applying other methods to create the groups of customers and take more variables into consideration.

Following this, and to be able to create new customers’ clusters, the data provided was analysed, cleaned, and organized. With those crucial steps done, the data set was finally ready to be process by the clustering algorithm (K-means). The data was also split into two different perspectives (geographical and funnel), so the insights into the clusters would be better and easier to interpret.

To help with interpretation and visualisation, PCA was also applied to the data so its dimensionality would be reduced.

After applying the K-means algorithm to both perspectives and merging them using hierarchical clustering, the solution obtained consisted of five clusters. These clusters were very different from each other and provided fertile soil to develop marketing tactics and targeting strategies.

## Cluster Descriptions

### Cluster 0 – National Workers:

* Lowest Revenue generated out of all others.
* Mainly Portuguese clients, who are not present on other clusters.
* Segment that books the closest to arrival.
* The lowest amount of People per Night, same for Rooms per Night, although the difference is more marginal.
* Considerable spending on Hotel Services.
* Corporate Funnel is the most appropriate funnel for targeting.
* Most attendance post booking.
* Clients in this segment have a very low special request count.

### Cluster 1 – European Spenders:

* Considerably high Revenue generated.
* Mainly French, British, and Southern Europe clients.
* The highest amount of People per Night, 2nd highest Rooms per Night.
* Considerable spending on Hotel Services.
* High attendance post booking.
* Significantly high special request count.
* Travel agencies and other operators are the most appropriate funnel for targeting.
* Direct funnelling could be explored, due to considerable frequency with a discount for booking on arrival, keeping higher margins.

### Cluster 2 – Traditional Travelers:

* Oldest segment out of all.
* Segment that books the farthest to arrival.
* Considerably Low Revenue generated.
* German clients, that are not present in other segments, and North and South American.
* Highest spend on Services, these customers should be targeted with tours, restaurant deals, massages, SPAs, and all existing service ranges available. Highest preference count.
* Travel Agencies should be the only ones considered for marketing campaigns.

### Cluster 3 – North American Clients:

* Highest spend on rooms, and lowest use of services, compared to room spend.
* Most Valuable cluster in Total revenue Count.
* Exclusively North American Clients.
* Use of booking on Arrival with the highest frequency.
* Marketing campaigns should be prioritised towards this cluster. Cluster 4 – Not so Simple Customers:
* Significantly high Revenue, Persons, and Rooms Booked per Night.
* Low demand for Hotel Services.
* Significantly high special request count.
* Segment with low regional differentiation, englobing Asian, African, Oceanic, and European clients.
* Highest use of booking on Arrival, and a significantly high count of Travel Agency Bookings.
