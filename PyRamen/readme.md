# Working out PyRamen

1. need to import csv

2. create a menu list to hold contents of menu_data.csv
    menu[] = read.menu_data.csv?
    menu = item, category, description, price, cost

3. create a sales list to hold contents of sale_data.csv
    sales = line item id, date, cc number, quantity, item

4. create a report dictionary with the metrics {count, revenue, cogs, profit}
    initalize variables
    count = 0
    revenue = 0
    cogs = 0
    profit = 0


5. split sales up into quantity and menu item, index 3,4 

    for x in sales:
        quanity = sales([3])
        menu_item = sales([4])

        if menu_item in report:
            quanity += 0
        else: 
            report[menu_item] = {
                count: 0
                revenue: 0
                cogs: 0
                profit: 0            
            }

    for ticker, ticker_data in new_records.items():
        # Set the new record to be added in list format
        record = [ticker_data['date'], ticker_data['open'], ticker_data['high'], ticker_data['low'], ticker_data['close']]    * 

6. # going through menu and adding in price and cost to report.

    for line in menu:
        item = menu[0]
        price = menu[3]
        cost = menu[4]
        if item in report:
            # do not use formulas from readme, they are not correct.
            quan = report[menu]["count"]
            report[item][revenue] += price * quan
            report[sales_item]["03-cogs"] += cost * quantity
            report[sales_item]["04-profit"] += profit * quantity
        else:
            print(item does not equal item sales item! NO MATCH!)


7. # adding results to text, should try print functions first to see if it works

print(report[0])



    with open("Report.txt", "w") as text:
        text.write("Sales Report for Ramen at PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")
        text.write("Sales Report for PyRamen")












END GOAL

1. dictionary = {

    key=item"item1: {
        01-count: random number,
        02-revenue: random number,
        03-cogs: random number,
        04-profit: random number
    }

    key=item"item2: {
        01-count: random number,
        02-revenue: random number,
        03-cogs: random number,
        04-profit: random number
    }

    key=item"item3: {
        01-count: random number,
        02-revenue: random number,
        03-cogs: random number,
        04-profit: random number
    }

    key=item"item4: {
        01-count: random number,
        02-revenue: random number,
        03-cogs: random number,
        04-profit: random number
    }

    key=item"item5: {
        01-count: random number,
        02-revenue: random number,
        03-cogs: random number,
        04-profit: random number
    }
}