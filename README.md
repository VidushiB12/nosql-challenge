# nosql-challenge

The database uk_food has one collection called establishments.

In part 1, find_one() function is used to find one document from the collection.
The establishments collection is stored in the variable establishments.

In part 2, the details for a new restaurant called Penang Flavours were stored in the dictionary called new_restaurant. insert_one() function is used to add the data in the establishments collection.

The BusinessTypeID for the business type Restaurant/Cafe/Canteen is found to be 1. This data was updated for the new restaurant using update_one. 

994 documents have LocalAuthorityName as "Dover" and they were deleted from the collection using delete_many function.

The data type was changed to float for latitude and longitude found in the geocode dictionary.
The data type for rating value was changed to integer.

In part 3, using respective queries:
41 documents had a hygiene score equal to 20.
33 establishments had London as Local Authority and rating value greater than 4.
Top 5 establishments close to Penang Flavours with rating value of 5 sorted by lowest hygiene are The Oak At Sockets Heath, Macchiatos, Essex Chef, Bourgee, Nancy's Sandwich Bar.





