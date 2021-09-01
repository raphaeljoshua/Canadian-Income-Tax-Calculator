income = 200000
if (income >= 0) and (income <= 48535):
        tax_total = (0.15*income)

elif (income > 48535) and (income <= 97069):
        tax_total = (0.15*48535) + (0.205 * (income-48535))

elif (income > 97069) and (income <= 150473):
        tax_total = (0.15*48535) + ((0.205*(97069-48535)) + (0.26*(income-97069)))

elif (income > 150473) and (income <= 214368):
        tax_total = (0.15*48535) + ((0.205*(97069-48535)) + (0.26*(150473-97069)) + (0.29*(income-150473)))

elif (income > 214368):
        tax_total = (0.15*48535) + ((0.205*(97069-48535)) + (0.26*(150473-97069)) + (0.29*(214368-150473)) + (0.33*(income-214368))) 

else: pass

print("I will pay:",tax_total, 'in taxes')
print("The amount I will pay in 1 month is:")
print(tax_total/12)
