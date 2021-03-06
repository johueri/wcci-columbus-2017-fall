## Creating a Shopping Cart using the ArrayList class

### The Item Class

Create an **Item** class that models an Item to be purchased. It should contain instance data and a constructor to hold the following characteristics: name, price and quantity. Item class should also include accessor methods for the 3 characteristics and a toString summary.

### The ShopApp Class

The **ShopApp** class should be designed to model shopping in similar fashion to Amazon and other online sites (where you can add to cart and you will see your total increase with each item added). Run a do while loop to simulate shopping, having the user enter the item, quantity and price. Store the items in an ArrayList and update the total due at checkout.

 **Stretch task**: Provide an opportunity to remove an item from the shopping cart if a user no longer desires to make that particular purchase.

#### Examples

```bash
Enter the name of the item: Shoes
Enter the unit price: 25
Enter the quantity: 2

Current Cart
Shoes		   25.0	    2		50.0
Total Price: $50.00

Continue shopping (y/n)? y
Enter the name of the item: Shirt
Enter the unit price: 15
Enter the quantity: 3

Current Cart
Shoes		   25.0	    2		50.0
Shirt		   15.0	    3		45.0
Total Price: $145.00

Continue shopping (y/n)? n
```
