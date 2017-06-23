# Recipt manual input

I haven't found any automatic way to extract each item and its price from a recipt.  
It would be nice to have this data and since I can't get it automatically, manually it is!  

This tool is to make manual input of recipt as easy as possible.

# Core features:
 - [x] Input of multiple recipts with the following data:
   - Date
   - Store
   - Items
   	 - Name
   	 - No. of item
   	 - Price
   	 - Modifier (Discount) 
 - [x] Export to JSON / CSV

# Usability features:
 - [ ] Autocompletion of store name
   - Auto save of new store names
 - [ ] Autocompletion of items
   - Auto save of new items
 - [ ] Tags for items
 - [x] See last recipt entered to the side (So that you don't forget which one you last entered)
 - [ ] Differentiate between price/weight and price/item
 - [x] Extra data on recipt
   - [x] "Person who bought"
 - [ ] Scroll down when adding new Item (Recipt can go way past the viewport)
 - [X] Add now() to export filename

# Minor fixes/bugs
 - [ ] When trying to click "save" it jumps down since a new form is created. Create the form on the "next" tab?
 - [ ] if deleting all data in the second to last form, the last form will be deleted even if there is data in it. Only remove empty forms


# Possible 2.0 version
Why not have some statistics and charts in the app?

 - [ ] Page where you can list, filter, edit and remove saved recipts
 - [ ] Page where you can see charts of your data
   - [ ] General statistics
     - Amount of money spent
     - Number of recipts =)
   - [ ] Different charts:
     - [ ] Price over time
     - [ ] Amount of items bought over time
     - [ ] Difference in price between stores
     - [ ] What weekdays do we shop on?
   - [ ] Ability to filter charts on
     - [ ] Date ranges
     - [ ] Tags
     - [ ] Stores
     - [ ] Persons