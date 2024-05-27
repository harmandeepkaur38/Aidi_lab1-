def calculate_compound_interest(principal, rate, time):
    """
    Calculate compound interest.
    
    Arguments:
    principal -- the principal amount (initial investment)
    rate -- the annual interest rate (in decimal)
    time -- the time period (in years)
    
    Returns:
    compound_interest -- the total amount after compounding the interest
    """
    compound_interest = principal * (1 + rate)**time
    return compound_interest

if __name__ == "__main__":
    principal = float(input("Enter the principal amount: "))
    rate = float(input("Enter the annual interest rate (in decimal): "))
    time = float(input("Enter the time period (in years): "))

    compound_interest = calculate_compound_interest(principal, rate, time)
    print("Compound interest after {} years: {:.2f}".format(time, compound_interest))# created by harmandeep kaur to demonstarte git bash skill 
