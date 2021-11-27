# Café Connect

## application which adds Café items to an order

This application will serve as the user interface side of a coffee shop order system. Users will be
able to add items from a coffee shop to an order.

*Additional features will include*:
- expanding items in the order
- removing items from the order
- editing items in the order. 

Potential users of this application are anyone who would like to order coffee from their local coffee shop.
This application might be later expanded as a portal to allow users to order from a selection of coffee
shops in their local area, with implementation varying based on each coffee shop's menu/ preferences.

I'm a big coffee guy, so this application is of specific interest to me. I also love going to new smaller
coffee shops and would be interested in an online order system for these that might otherwise be available
for larger cafés like Starbucks or Tim Hortons.

## User Stories

Phase 1:

- As a user, I want to be able to add a new drink to my order
- As a user, I want to be able to remove a drink from my order
- As a user, I want to be able to view my order
- As a user, I want to be able to modify existing items in my order

- As a user, I want to be able to include add-ons to an item in my order,
  say sugar or an espresso shot
- As a user, I want to be able to view the drink menu
- As a user, I want to be able to increment a drink in my order
- As a user, I want to be able to view a specific drink in my order


Phase 2:
- As a user, when I select quit from the application menu, I want to be reminded
  to save my order and have the option to do so or not
- As a user, when I start the application, I want to be given the option to load
  my order from file

source: The persistence code for this project is based on the JsonSerializationDemo project.

source: Icon "coffee_cup.png" made by Freepik from www.flaticon.com


Phase 4: Task 2

    drip coffee has been added to the order
    Fri Nov 26 16:47:13 PST 2021
    
    drip coffee has been removed from the order
    Fri Nov 26 16:47:16 PST 2021
    
    drip coffee has been added to the order
    Fri Nov 26 16:47:20 PST 2021
    
    americano has been added to the order
    Fri Nov 26 16:47:22 PST 2021
    
    americano has been removed from the order
    Fri Nov 26 16:47:26 PST 2021
    
    Order saved to file ./data/currentOrder.json
    Fri Nov 26 16:47:29 PST 2021
    
    Order complete.
    Fri Nov 26 16:47:31 PST 2021

Phase 4: Task 3

- I don't think my project needs significant refactoring, as I did a lot of that while I wrote my code.
- I could refactor the OrderPanel class into two classes since it contains two panels: DrinkList and
OrderSummary side by side which perform two different things.