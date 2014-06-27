# [Single-Order Processing](id:top)
Generally, orders from single sold-to customers, such as landscapers and small garden centers, fit in this category. See which [setup](setup:orders) procedures you may need to complete before processing orders.

## Single-Order Processing: Overview
The following sections explain the basic procedures for processing an order for a single sold-to customer, from entering to posting an order.

|**Step-by-Step Procedures**|**Where to Go?**|
|:------|:----------|
|Enter a shipping order (independent of a master). [Help](#orderentry) | Orders > Entry Forms |
| Print a confirmation. [Help](#documents) | Orders > Documents |
| Pull: Order a pull report and/or print tags. [Help](#pull) | Orders > Documents |
| Load: Print load list and/or customer labels. [Help](#documents) | Orders > Documents |
| Revise order based on what was loaded. [Help](#editorder) | Orders > Entry Forms |
| Deliver: Print packing list. [Help](#documents) | Orders > Documents |
| Update inventory: Make order pick edit list and change locations. Post pick list. [Help](#picklist) | Orders > Order Posting |
| Send order to Receivables to close order. [Help](#post) | Orders > Order Posting |
| Print invoice. [Help](#documents) | Orders > Documents |

The above series of steps takes place in the Orders module. To continue processing an order through customer payments and bank deposits, follow these steps:

|**Step-by-Step Procedures**|**Where to Go?**|
|:------|:----------|
| Enter customer payment and apply to invoice. [Help] (receivables: payments) | Receivables > Payments, Receipts, and Prepaids |
| Make a bank deposit. [Help] (receivables: deposit) | Receivables > Payments, Receipts, and Prepaids |

# Order Entry: Shipping Orders 
Shipping orders that are not tied to a master order generally come from landscapers and garden centers. The customer may pick up the order or have it delivered, but not use a large-scale carrier. You can print the order to use as an invoice, with the customer paying by cash or on account. Click here (#multiorder processing: shipping from master) to learn how to enter a shipping order from a master.

## [Enter a Shipping Order (not from Master)](id:orderentry)
1. Go to Orders > Entry Forms > Shipping Orders.  
2. Select “Insert.”  
3. Fill in information about the order. The following fields are required: Order Date, Product Type, Ship-To/ Sold-To, Want Date.  
 	*Click here (options: masterorder) to learn how to change default settings for these fields.
4. Click “Save.”
5. Select “Detail” and then “Insert” to add products and quantities. CompuPlants offers four options for accessing product inventory:

	a. The **Current Order** tab allows you to select from a drop down list of your entire product inventory. Select a product from the list (double-click or hit Enter). Type quantity, then Enter.

	b. The **Availability** tab provides a drop-down list of available inventory. Select a product from the drop down list and type quantity. Double-click to add to order.

	c. The **Master Order** tab references the master order, if there is one, for this customer. Select an order number from the drop down list and double-click it to add to the current order. Click on the grid to change quantities.
	
	d. The **Shipped Orders** tab presents a list of products this customer has made in the past. Select an order date range, then double-click on a product to 
	copy it to the current order. Click on the grid to change quantities.

	e. Customize Tab???

6. Create a new detail page for each product ordered.
	*Use the shortcut, plus sign (+), to quickly save details and open a new detail page.

After you’ve entered all products, view a summary of the order by selecting “Summary” in the toolbar. To learn how to print documents associated with the order, such as a confirmation or invoice, click [here](#documents).

###Duplicate Products
When putting together large orders, it can be easy to accidentally duplicate product entries. CompuPlants has a built-in feature that prevents users from adding the same product twice. Sometimes the duplication is intentional, for instance, during promotional pricing. 

**To intentionally duplicate a product:**

1. Use the “Current Order” tab on the Detail page to add the duplicate product.
2.  _Choose the appropriate category_ (between “Product” and “Quantity”) and type the quantity. This enables the application to differentiate between two products that otherwise appear identical.

### [Edit/Revise a Shipping Order](id:editorder)
1. From Orders > Shipping Order, conduct a query. 
2. Double-click the order of interest on the grid, or single-click to highlight then click “Detail.” 
3. Make adjustments to the order and click “Save,” if necessary.

### Quick-Change Order Details
Easily change some information pertinent to a shipping order, such as price and current quantity, using a quick-change grid. Note that the grid does not allow you to add or delete products. Follow this path to access the grid: **From Orders > Entry Forms > Quick Change Order Details**.

### Changes by Order Report
This report allows you to see changes made to an order in progress, such as what products were added and/or deleted, changes in pricing, and the author of those changes.

1. Go to Orders > Change Order Reports > Changes by Order.
2. Select a report design and date range.
3. Click “Find.”
4. Double-click the order of interest to view the report.

### Cancel a Shipping Order (do you want this in here?)
1. Go to Orders > Duplicate, Cancel and Back Orders > Cancel an Order.
2. Enter the order number in the required field.
3. Select the desired action:
	* “Move Order to Cancel History” removes it from Orders while maintaining a record of it. 
	* “Cancel Order” deletes the record.

[Top of Page](#top)
<br></br>
# Order Documents
Orders > Documents gathers all of the order-related documents in one convenient place to help you save time.

## [Orders 5.6](id:documents)
This feature allows you to print documents that you created in Setup > Orders > [Documents] (setup: documents). These could include _**quotes, order acknowledgments, order confirmations, proof copies, invoices, load lists, packing lists, bills of lading, etc.**_

**To print a document:**

1. Select the design number and document number. Click “Find.”
2. Double-click the order row to preview the document, then print.
3. Repeat the process to print a different type of document.


## [Order Pull Report](id:pull) 
This report organizes a pull for a single shipping order. It shows available locations for each product, along with available quantities by location. (How does the program select locations?)

**To order a pull report:**

1. Enter a design number. 
2. Select sorting criteria.
3. Check the box labeled “print only where shipped greater than zero” to remove any unavailable items from the report. 
4. Preview and/or print.

You may opt to print product **tags** at this time. Click [here](#tags) to learn how.

## Mass Pull Report
This report increases efficiency by organizing a pull for multiple shipping orders at once, but does not require building a truck. Customers may pick up the orders or have them delivered by a smaller truck.

**To conduct a mass pull by order:**

1. Leave the order number field blank.
2. Select print and group criteria.
3. Select multiple orders from the grid by holding down the Control key and highlighting individual orders. 
4. Preview and/or print.

[Top of Page](#top)
<br></br>
# Tags & Labels


## [Print Tags](id:tags) 


## [Print Labels](id:labels)

<br></br>
[Top of Page](#top)


#[Order Posting](id:orderposting) 

## [Pick List](id:picklist)
A pick list allows you to update inventory quantities by location after shipping an order. Generally, customers create a pick list after pulling products from the field to record how many plants were actually taken from each location. Some customers, however, make a pick list before running a pull report and designate specific locations for pulling inventory. If you prefer the latter method, opt to print a single location in [setup] (setup: picksource).

### Make Pick List
1. Go to Orders > Order Posting > Make Order Pick Edit List. (naming)
2. Type the order number and select “Execute.” The system stores the pick list.

### Edit Pick List
1. Go to Orders > Order Posting > Edit Pick List.
2. Type the order number and click “Find.” The top grid displays the pick list that you are editing. The bottom grid displays available locations for the highlighted product in the pick list. 
3. Change locations and quantities: 

	a. Highlight a product row in the pick list. 

	b. Double-click a location row from the bottom grid and changes will be applied to the pick list. The chosen location will display a green background after it is applied.

4. If a product was pulled from multiple locations:

	a. “Copy” the product. This produces another row with the same product information in the pick list. 

	b. Change the quantities for each pull. 

	c. Set a location for each pull.
5. (Optional) Select “Verify.” This sums up the “Picked” column and compares it to the sum of the "To pick" column. If the totals disagree, the background color in the upper grid rows turns green.

**Note:** If an order is changed after a pick list has been made, you must make another pick list and edit locations. If you pre-select locations for pulling using a pick list, creating a new pick list will only affect the product that has been changed. Locations for all other products will remain the same. wording??

### Post Pick List to Inventory
1. Go to Orders > Post Inventory.
2. Type the order number and select “Execute.” To run a trial post first, un-check the box labeled “post inventory.”

Do not post with NF is not an option for this post. Should it be?

Un-post Pick List?


## [Post Order to Receivables](id:post) 
 Post an order to receivables to close it once it has shipped.

1. Go to Orders > Order Posting > Post Orders.
2. (Optional) Run a trial post to see if any errors exist by unchecking the box labeled “Post Order.” Check the box when the order is ready to post.
3. Enter the order number and the invoice post date.
4. Click “Execute.” 
If an error prevents the order from posting, the application will display a red X and describe the error. If there is no error, check the “Post Orders” box and click “Execute.”

Change Order after it Posts?

<br></br>
[Top of Page](#top)
