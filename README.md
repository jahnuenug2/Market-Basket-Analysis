# Market-Basket-Analysis
Market Basket Analysis

INTRODUCTION

Market basket analysis explores the relationship between products by considering the co-occurrence of purchases in previous transactions.
Market basket analysis is a process that looks for relationships of objects that “go together” within the business context.
Market basket analysis is the analysis of any collection of items to identify affinities that can be exploited in some manner.
Market basket analysis is a process that looks for relationships among entities and objects that frequently appear together, such as the collection of items in a shopper’s cart.
Product placement - Identifying products that may often be purchased together and arranging the placement of those close by to encourage the purchaser to buy both items. 
That placement can be physical, such as in the arrangement of products on shelves in a brick-and-mortar location, or virtual, such as in a print catalog or on an e-commerce site.
Point-of-Sale—Companies may use the affinity grouping of multiple products as an indication that customers may be predisposed to buying certain sets of products at the same time. 
This enables the presentation of items for cross-selling or may suggest that customers may be willing to buy more items when certain products are bundled together.
Customer retention—When customers contact a business to sever a relationship, a company representative may use market basket analysis to determine the right incentives to offer in order to retain the customer’s business.


ALGORITHMS

Apriori Algorithm:
The Apriori algorithm is a popular data mining technique used to identify frequently occurring item sets in a dataset.
 The algorithm is based on the principle that if an item set is frequent, then all of its subsets must also be frequent. 
By leveraging this observation, the algorithm is able to narrow down the search space and avoid searching through all possible item sets, which can be computationally expensive.

ECLAT Algorithm:
The ECLAT (Equivalence Class Clustering and Bottom-Up Lattice Traversal) algorithm is a popular algorithm in data mining for finding frequent item sets in a dataset. 
Like the Apriori algorithm, it is based on the observation that if an item set is frequent, then all of its subsets must also be frequent. 
However, the ECLAT algorithm takes a different approach to generate frequent item sets.

Data Collection

The data is collected from the Oye-happy organization which is an online store of personalized gifts.
The data is loaded and formed into a new data frame by using label encoding of the description column and them implementing the algorithms on the new data frame named basket_sets.






