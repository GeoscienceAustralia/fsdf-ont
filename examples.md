# Examples
#### Of how to use the FSDF-O

## E.G. 1: G-NAF & Geofabric relations
We already have a prototype Semantic Web version of the Geocoded National Address File (G-NAF, see <http://gnafld.net>) and we have previously had a Semantic Web version of the Geofabric (see <http://www.bom.gov.au/water/geofabric/>). Without going into the details of the structure of these datasets, something a serious user of them would surely need to do, how can we know about their relationships, if any, in accordance with FSDF?  

There are two answers to this. One involves the data stored in the [LINK](http://link.fsdf.org.au) and, hopefully soon, distributed data stored within various jurisdictional catalogues in Australia. This first answer will allow us to discover if there are any dependency or governance relationships between the G-NAF & Geofabric via provenance information: is the G-NAF dependent on anything that the Geofabric is, or vice versa? Are either dependent on the other? Are they both dependent on any common organisations?

![G-NAF & Geofabric provenance relationships](example-01a.png)  
![G-NAF & Geofabric provenance relationships](example-01b.png)  
**Figure 1**: G-NAF (top) & Geofabric (bottom) provenance relationships from [LINK](https://link.fsdf.org.au). Note there are no common ancestors or Agents (organisations).

The second way we can look for relationships is via the data *within* the datasets: are any items in the G-NAF referenced by those in Geofabric, or vice versa? The FSDF-O requires that any such
This ontology models relationships in two ways: the dataset/governance viewpoint and the class viewpoint. For the first, we can see that there is little direct relation (they share no similar creator agencies or  ancestor datasets or tools)

!(G-NAF & Geofabric class relationships)[example-2.png]
Figure 2: G-NAF & Geofabric class relationships
