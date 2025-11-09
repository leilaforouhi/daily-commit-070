def add_tax(price, tax_percent):
    tax_amount = price * (tax_percent / 100)
    final_price = price + tax_amount
    return final_price

if __name__ == "__main__":
    price = 300
    tax = 9
    print(f"Final price after {tax}% tax: {add_tax(price, tax)}")
