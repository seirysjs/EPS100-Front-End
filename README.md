# EPS100 Front-End
Application is based on ` Node.js ` + ` Vue.js `

### Project Setup

```
npm install

npm run serve
```
------------------
### To-Do:

* Screenshots
------------------
### Partials
<br>

* `TopMenu` (Site's Navigation / Menu Bar)
* `DataTable` (Component for Processing Array to Paginated Data Table)
------------------

### Pages

* `Login` (Page to Enter Your Credentials and Verify them) 
<br>

* `BlockList` (Default Route / Home Page Containing Paginated Blocks Data Table)
* `BlockNew` (Page with Form to Register New Block)
* `BlockDetails` (Summary, Actions, Details of Block Entity Entry)
* `BlockEdit` (Form Page to Edit Block Entry) 
* `BlockProcess` (Form to Register Cut Processing of Block to Products)
* `BlockMultiCut` (Form to Register Cut Processing of Multiple Blocks to Products)
<br>

* `ClientList` (Page Containing Paginated Clients Data Table)
* `ClientNew` (Page with Form to Add New Client)
* `ClientDetails` (Summary, Actions, Details of Client Entity Entry)
* `ClientEdit` (Form Page to Edit Client Entry) 
<br>

* `InventoryClassList` (Page Containing Product Class Inventory Data Table + Summary)
* `InventoryClassBlueprintsList` (Page Containing Inventory Products Data Table)
* `InventoryDetails` (Summary, Entries, Details of Inventory Product)
<br>

* `OrderList` (Page Containing Paginated Orders Data Table)
* `OrderNew` (Page with Form to Create New Order)
* `OrderDetails` (Summary, Actions, Details of Order Entity Entry)
* `OrderEdit` (Form Page to Edit Order Entry) 
<br>

* `OrderFulfill` (Fulfil Order Items / Designate Inventory Products for Delivery & Invoice)
* `OrderInvoice` (Page to Issue New Items Transfer Invoice)
* `OrderInvoiceEdit` (Form Page to Edit Invoice Entry) 
<br>

* `OrderBill` (Page to Form New Order Billing Invoice)
* `OrderBillDetails` (Summary, Actions, Details of Bill Entity Entry)
* `OrderBillEdit` (Form Page to Edit Bill Entry) 
* `BillPayment` (Page To Register Received Payment Amounts for Bill)
* `BillPaymentEdit` (Form Page to Edit Bill Payment Entry)
<br>

* `OrderInvoiceList` (Page Containing Paginated Transfer/Invoices Data Table)
* `OrderBillList` (Page Containing Paginated Billing/Bills Data Table)
<br>

* `PricesList` (Page Containing Paginated Array of PriceLists Data Table)
* `PriceListNew` (Page with Form to Create New Price List)
* `PriceListDetails` (Summary, Actions, Details of PriceList Entity Entry)
* `PriceListEdit` (Form Page to Edit Price List Entry) 
<br>

* `ProductClassList` (Page Containing Paginated Product Classes Data Table)
* `ProductNewClass` (Page with Form to Add New Product Class)
* `ProductClassDetailsList` (Page Containing Paginated Product Class x Dimensions Data Table)
<br>

* `ProductSizesList` (Page Containing Paginated Product Dimensions Data Table)
* `ProductNewSize` (Page with Form to Add New Product Dimensions)
* `ProductSizeDetailsList` (Page Containing Paginated Product Dimensions X Class Data Table)
<br>

* `ProductList` (Page Containing Paginated Products Data Table)
* `ProductNew` (Page to Form New Product Blueprint)
* `ProductDetails` (Summary, Entries, Details of Blueprint Entity Entry)
<br>

* `TransportDetails` (Summary, Actions, Details of Transport Entity Entry)
* `TransportEdit` (Form Page to Edit Transport Entry) 
* `TransportList` (Page Containing Paginated Transports Data Table)
* `TransportNew` (Page with Form to Add New Transport Vehicle)
<br>

* `WorkerDetails` (Summary, Actions, Details of Worker Entity Entry)
* `WorkerEdit` (Form Page to Edit Worker Entry) 
* `WorkerList` (Page Containing Paginated Workers Data Table)
* `WorkerNew` (Page with Form to Add New Worker)
------------------
### UI Functions
<br>

* `authHeader` (Get Local Storage's Data for Existing User Session)
* `defineStore` (Initialize Reactive Storage for User's Session State)
* `dateToLocaleDateString` (Transform Raw `Date` to Format: yyyy-mm-dd)
* `dateToLocaleString` (Required for Raw `Date` Conversion to Html Datetime Input Value)
* `countVolumeBlueprint` (Calculate M3 Volume for Specific Product's Blueprint)
* `countInvWarehouseItemVolume` (Calculate M3 Volume of Single Warehouse Item Blueprint)
* `countInvOrderItemVolume` (Calculate M3 Volume of Single Order Item Blueprint) 
* `countInvTotalItemVolume` (Calculate Total M3 Volume Of Blueprint's Inventory+Order Items)
* `ordersInQueueCount` (Filter & Count `In Queue` Orders)
* `ordersInWIPCount` (Filter & Count `Active` Orders)
* `totalVolumeOrderItems` (Calcucale & Stack M3 Volume of Order's Items `Array`)
* `totalVolumeTransfers` (Calcucale & Stack Total M3 Volume of Order's Transfer Invoices `Array`)
* `totalVolumeBills` (Calcucale & Stack Total M3 Volume of Order's Billing Invoices `Array`)
* `roundNumber` (Round `number` Value, `scale: 3`)
* `mapOrderItemsByBlueprints` (Map Order's Items `Array` by Blueprint to `Object` With Tagged Blueprints)
* `mapOrderItemFulfillsByBlueprints` (Map Fulfilled Order's Items `Array` by Blueprint to `Object` With Tagged Blueprints)
* `sortBlueprintsByClassNames` (Sort `Array` of Blueprints by Product Class Name)
* `sortBlueprintsByActualSizes` (Sort `Array` of Blueprints by Product Dimensions)
* `sortInvBlueprintsByActualSizes` (Sort `Array` of Inventory Products by Blueprint Dimensions)
* `ltBlockStatus` (Translate English Block Status to Lithuanian)
* `ltOrderStatus` (Translate English Order Status to Lithuanian)
* `ltEnabled` (Translate English Enabled Status to Lithuanian)
* `groupByKey` (Reduce/Reassign `Array` of `Objects` By Provided Key Value)
* `billPaymentsDue` (Calculate Payments Due `Date` for Bill from Delivery `Date` + Postpone Duration in Days)
* `totalAmountPayments` (Parse `Array` of Payments Received & Count Total Amount, `scale: 2`)
* `totalAmountBills` (Parse `Array` of Bills & Count the Total Amount of Order's Bills)
* `roundNumberScaleTwo` (Round `number` Value, `scale: 2`)
* `amountProductBillItemsTotal` (Parse `Array` of Bill's Items & Calculate the Total Price Amount)
* `amountProductOrderBillsItemsTotal` (Parse `Array` of Order's Bills & Calculate the Total Payments Amount Due)

------------------
### API
https://github.com/seirysjs/EPS100-Front-End/blob/master/src/lib/api.js
