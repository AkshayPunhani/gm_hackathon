## General Motors Hackathon Machine Learning@Berkeley
#### About
Due to enormous volume of raised defects, it is not feasible to fix all the concerns within the confines of launching a product quickly, and indeed some issues may never be addressed. Today, defect prioritization is done by highly skilled engineers with significant experience in the field – however, this process is inefficient and leads to an overlap between true customer sentiment and personal experiences. This tribal knowledge is difficult to transfer to new engineers as more experienced engineers progress in their careers. It can take years for a new engineer to become proficient at the defect prioritization process.

Provided with some sample engineering defects and the list of customer complaints, the goal was to discover the relationship between customer complaints and engineering defects. To tackle the problem, we were supposed to build a model that's capable of discovering this relationship.

### **Data** 
Customer Complaint Data - Each customer complaint has a detailed description, sample customer verbatim, and engineering defects that match the complaint
Engineering Defects - Sample engineering defects that are potentially related to customer complaints

Train.csv - The training set contains customer verbatims, other structured data fields which may be used as inputs, and target area/sub area each one belongs. The variable to model for this exercise is labeled “area” and “subarea”.
