# calculator
This is my first Python calculator,  it calculates how much it will cost to drive a certain distance by car.
a = float(input("Cost of fuel per 1L: "))
b = float(input("Fuel consumption per 100 km: "))
c = float(input("Distance: "))
total = round(c / 100 * b * a, 2)
print("Total amount:", total)
