# RoRo_Spot

Dataset of instances for numerical experiments

**Meaning of the txt title:**
Instance set _ No. of instance _ information _ Number of spot orders

For example: "U1_1_information_5" refers to the first instance in set U1, which is configured with 5 spot orders.

**Meanings of each item in txt:**

PortNum: The total number of ports in the sailing route

DeckNum: The total number of decks

LaneNum_each_deck: The number of lanes arranged on each deck

Length_each_lane: The length of each lane (in length unit)

OrderNum: The total number of transportation orders

Information_each_order:
number of vehicles | length of a vehicle | weight of a vehicle | Origin of vehicles | Destination of vehicles

ShiftingCost_each_Order: The cost of shifting a vehicle in each order

Revenue_each_SpotOrder: The revenue of executing each spot order

Epsilon: Coefficient controling the space utilization of contractual orders between any two adjacent ports
