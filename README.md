# python2
def calculateTax(salary,percent=20):
    taxAmount = salary*percent/100
    print(taxAmount)

x=int(input("salary:"))
y=float(input("tax percent:"))

calculateTax(x)
calculateTax(x,y)

