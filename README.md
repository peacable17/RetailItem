# RetailItem
#RetailItem Chap 9 Homework

class RetailItem(object):
    def _init_(self):
        self.description = 0
        self.inventory = 0
        self.price = 0
        
item1 = RetailItem()
item1.description = 'Jackets'
item1.inventory = 12
item1.price = 59.95
    
item2 = RetailItem()
item2.description = 'Designer Jeans'
item2.inventory = 40
item2.price = 34.95

item3 = RetailItem()
item3.description = 'Shirts'
item3.inventory = 20
item3.price = 24.95
    
print('Item: %s Qty: %d Price: $%f \n' %(item1.description,item1.inventory,item1.price))

print('Item: %s Qty: %d Price: $%f \n' %(item2.description,item2.inventory,item2.price))

print('Item: %s Qty: %d Price: $%f \n' %(item3.description,item3.inventory,item3.price))
