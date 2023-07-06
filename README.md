# TotalExpenses
T = int(input())
for i in range(T):
    quantity, price = map(int, input().split())
    total_expense = price * 0.9 * quantity if quantity > 1000 else price*quantity
    print(total_expense)
