import random

def get_numbers_ticket(min_number, max_number, quantity):
    
    if quantity > (max_number - min_number + 1):
        return []
    elif min_number < 1 or max_number > 1000:
        return []
    elif min_number > max_number:
        return []


    ticket_numbers = set()
    for n in range(quantity):
        ticket_numbers.add(random.randint(min_number, max_number))

    return sorted(ticket_numbers)

print("Ваші лотерейні квитки: ", get_numbers_ticket(20, 1000, 5))