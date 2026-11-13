# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
### Project Title or Name of the Application	:
### Section			   	      :
### Group Members			    :
### Date (Proposal Date)  : Nov 5, 2026
### Project Description:

 This project aims to develop an OOP simulation of a Food Delivery Service System designed to provide a convenient, and seamless solution for consumers to be able to buy food without leaving the comfort of their homes. The system is designated to help those who are sick, busy employees, students, elderly individuals, and those who simply want to enjoy the taste of a fast food meal within their homes. Through this app, consumers can search for restaurants based on their preferred type of cuisine, view available dishes, and place food orders. The app will also provide the estimated travel time of the delivery unit, which can allow customers to see how long it will take for their food to arrive.

**Person:**
    Attributes: name, address
    Methods: get_name(), set_name(), get_address(), set_address()
      **Customer:**
        Attributes: Name, Address, Payment_method
        Methods: place_order(restaurant, dish), add_payment(amount), receive_dish(), eat_dish(), rate_restaurant(restaurant, score), rate_delivery_unit(delivery_unit, score)
**Restaurant:**
    Attributes: Name, CuisineType, Location, OperatingHours, Menu, AverageRating, TotalReviews
    Methods: get_cuisine_type(), set_cuisine_type(cuisine_type), check_availability(time), receive_order(order), prepare_dish(), estimate_prep(), call_delivery_Unit(delivery_unit), update_rating(new_score)
**DeliveryUnit:**
    Attributes: PlateNumber, Status, Rating
    Methods: receive_dish(), change_status(), give_dish(), ETA(distance), update_rating(new_score)
      **MotorcycleUnit:**
          Attrubutes:
          Methods: ETA(distance)
      **CarUnit:**
          Attributes: 
          Methods: ETA(distance)
**Application:**
    Attributes: registered_restaurants, available_cuisines
    Methods: search_restaurants(cuisinetype, time), search_cuisines(), confirm_payment(customer, amount), calculate_ETA(restaurant, deliveryunit, distance)

Our primary target demographic includes individuals with either limited mobility, tight schedules, or simply not wanting to leave their home to buy food. This includes but is not limited to busy office workers, students, elderly residents, sick individuals, and urban residents.

The customer first uses the app to search for what cuisine or restaurant they would like to order from. They will then pay through the app and wait until the payment gets confirmed before the order is sent to the restaurant where they will receive it. The restaurant will prepare the dish and call a delivery unit to deliver it to the address of the customer. Meanwhile, the customer can see where their food is by checking the app and confirming the status of their order. The delivery unit will then arrive at the address and give the food to the customer. After receiving it, the customer can now eat and enjoy the prepared dish.


https://drive.google.com/file/d/1dqpSB_vtipZXrCaj53KrArTEbchqGomM/view?usp=sharing 
### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

Objective 1: Create an application that enables customers to search for restaurants based on preferred cuisine types, view available restaurants during specific hours of the day, and conveniently place food orders while removing the need to physically visit the establishment.
Objective 2: Develop a system that allows restaurants to receive customer orders, prepare food, and request delivery units to transport the orders to the correct customer locations.
Objective 3: Implement features that show the restaurant’s estimated time for food preparation and the estimated delivery time for the assigned units so customers can have an idea when their order will arrive.
Objective 4: Implement OOP principles, such as Encapsulation, Inheritance, Polymorphism, and Abstraction, ensuring a maintainable code.
Objective 5: Integrate input validation and error handling (such as setters and getters) to guarantee smoother user experience and prevent runtime failures during code order execution.

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
