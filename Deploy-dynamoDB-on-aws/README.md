# Type DynamoDB in the search bar and choose to open the DynamoDB console.
<img src="https://github.com/Voldarco/AWS-Practice/blob/5b173822e079323340cf8a0d927cd3c64163ba9a/Deploy-dynamoDB-on-aws/Screenshot%20(70).png" >

##  In the DynamoDB console, choose Create table.
<img src="https://github.com/Voldarco/AWS-Practice/blob/5b173822e079323340cf8a0d927cd3c64163ba9a/Deploy-dynamoDB-on-aws/Screenshot%20(71).png">

### In the table section I use a content with a wide area to cover that generalize my chosen topic. The partition key is used to spread data across partitions for scalability.<br> It’s important to choose an attribute with a wide range of values that is likely to have evenly distributed access patterns. You can also enable easy sorting with a sort key like I did to make queries organised during a search in cases of a large data volume
![Screenshot (73)](https://user-images.githubusercontent.com/69207791/208241152-30cb208f-a0f9-4275-a0bf-53de6654b64e.png)

### I leave the rrest of the settings at default due to the fact that this is a test project with the default being good enough. Now choose Create table.
![Screenshot (74)](https://user-images.githubusercontent.com/69207791/208241617-4683c718-a06f-4df7-948d-dc866e5c3eeb.png)

# Adding data to your new DynamoDB table.
## Select Explore items from the left menu, then select the radio button next to the Schools table and click create item.
![Screenshot (75)](https://user-images.githubusercontent.com/69207791/208241721-a3cb0f81-d157-4824-8cb9-5ffcfe77f133.png)

 ### In the data entry window input values corresponding to the attributes created by you or requested by the company.<br> Note that you can also add additional data entries.
 ![Screenshot (76)](https://user-images.githubusercontent.com/69207791/208241752-b3aec11b-8978-4428-b40e-46d27ca2fdee.png)
 ![Screenshot (77)](https://user-images.githubusercontent.com/69207791/208241754-7a5b9c86-20bc-4893-87ca-ff1011af2a67.png)
 ![Screenshot (78)](https://user-images.githubusercontent.com/69207791/208241756-e3422f04-db7b-46f5-b372-d963f289afeb.png)
# How to Query the database for information.
## In DynamoDB, query operations are efficient and use keys to find data while Scan operations traverse the entire table showing all contents.
### click on the query button, navigate to the attributes and input the values your are looking for.<br> click on run and the item will be found.
![Screenshot (79)](https://user-images.githubusercontent.com/69207791/208241758-7ce3bdd6-950a-4b0a-b31a-f80dff6f8289.png)
### I also noticed the query is case sensitive so it is advicable to save data entires in small letters.
![Screenshot (80)](https://user-images.githubusercontent.com/69207791/208241746-b64ada5e-1889-42ac-9eec-17031a59e519.png)
### You can also query with a single letter when looking for related entries.
![Screenshot (81)](https://user-images.githubusercontent.com/69207791/208241747-e503d979-a834-4797-a5bd-11675cbddec6.png)

#  Delete an item from your DynamoDB table.
## Change the Query dropdown list back to Scan. 
### Items can be deleted after selecting all neccessary items to deleted. Locate the Action dropdown and select delete among the option. This will permanently remove all the selected items on your list

![Screenshot (82)](https://user-images.githubusercontent.com/69207791/208241749-2253e0d7-5bfa-4f87-9f48-aa1dce7d8336.png)

# Delete your DynamoDB table.
## You can easily delete a table from the DynamoDB console.<br> It is a best practice to delete tables you are no longer using so that you don’t keep getting charged for them.

### In the DynamoDB console, select the checkbox of the tables you want to delete and then choose Delete.<br> Note no reversal once deleted
### In the confirmation dialog box, enter the text delete and click Delete button.
![Screenshot (83)](https://user-images.githubusercontent.com/69207791/208241751-747df7ff-b563-4b43-80b9-bdca44e73226.png)

# The end.
