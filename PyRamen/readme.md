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


5. split sales up into quantity and menu item, index 3,4 (STILL NEED TO WORK ON HOW TO ADD UP QUANITY UHGGGGGGHHGHGHHGHGHG)

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

6. 











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