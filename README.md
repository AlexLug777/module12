# module12
money = int (input ("Enter the amount you plan to deposit with interest:"))
per_cent = {'TKB': 5.6, 'SKB': 5.9, 'VTB': 4.28, 'SBER': 4.0}
TKB = int ((per_cent ['TKB']) * (money / 100))
SKB = int ((per_cent ['SKB']) * (money / 100))
VTB = int ((per_cent ['VTB']) * (money / 100))
SBER = int ((per_cent ['SBER']) * (money / 100))
deposit = [TKB, SKB, VTB, SBER]
print ("Accumulated funds for the year of deposit in each of the banks =", deposit)
print ("The maximum amount you can earn is:", max (deposit))
