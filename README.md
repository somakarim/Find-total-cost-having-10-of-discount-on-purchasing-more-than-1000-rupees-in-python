# Find-total-cost-having-10-of-discount-on-purchasing-more-than-1000-rupees-in-python
quantity= input('Enter Quantity: ')
total=100*int(quantity)
print('Your bill is:',total)
if int(total)>1000:
    discount=(10/100)*int(total)
print('Your Discount is: ', discount)
    bill=total-discount
print('Your bill after discount is: ', bill)
else:
print('No discount.')
