Download Link: https://assignmentchef.com/product/solved-dakine-sports-store-c
<br>
C++ program to keep track of a sports store inventory. The store sells various items. For each item in the store, the following information is kept, item ID, item name, number of pieces ordered, number of pieces currently in the store, number of pieces sold, manufacturer’s price for the item and the store’s selling price. At the end of each week, the store manager would like to see a report in the following format:

<strong>Dakine Sports Store Report</strong>

<strong>ItemID itemName</strong> <strong>pOrdered</strong> <strong>pInstore  pSold</strong> <strong>manufPrice  sellingPrice</strong>

<strong>1111 Basketball 100 100 20 10.00 30.00</strong>

<strong>2222 Frisbee 75 75 10 5.00 15.00</strong>

<strong>Total Inventory: $######.##</strong>

<strong>Total number of items in the Store: ————————</strong>

The total inventory is the total selling value of all of the items currently in the store. (for what is listed in the report above the value would be 3375.00(80 *30.00 + 65*15.00)

The total number of items is the sum of the number of pieces of all of the items in the store. for what is listed in the report above the value would be 145(80+65)

Your program must be menu driven, giving the user various choices such as:

<strong>Welcome to the Dakine Sports Store!</strong>

<strong>Choose from the following options.</strong>

<strong>1: To see if an item is in the store (search by name of the item entered).</strong>

<strong>2: To buy an item (ask for the name of the item and then how many the buyer wants to purchase, output how much the buyer owes).</strong>

<strong>3. To check the price of an item (ask for the name of the item).</strong>

<strong>4: To print the inventory (print the inventory report.</strong>

<strong>9: To end the program.</strong>

Initially, the number of pieces (of an item) in the store is the same as the number of pieces ordered, and the number of pieces of an item sold is zero. Input to the program is a file consisting of data in the following form:

<strong>1111 Basketball 100 100 20 10.00 30.00</strong>

<strong>2222 Frisbee 75 75 10 5.00 15.00</strong>

<strong>3333 Baseball 100 100 40 7.00 21.00</strong>

<strong>4444 Baseball bat 150 150 100 12.00 36.00</strong>

After inputting the data, sort it according to the items’ names. Also after an item is sold, update the appropriate counts.

Use seven parallel vectors to store the information. The program must contain at least the following functions: one to input the data into the vectors, one to display the menu, one to sell an item, and one to print the report for the manager