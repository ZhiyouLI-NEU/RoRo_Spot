# RoRo_Spot

Dataset of instances for numerical experiments

Meaning of the txt title:

Instance set _ No. of instance _ Ship size _ Total number of transportation orders _ Number of spot orders

For example: "S1_1_Small_11_8" refers to the first instance in set S1, which is configured with a small-sized ship and 11 transportation orders. In the instance, 8 transportation orders are spot orders.

Meanings of each item in txt:

PortNum: The total number of ports in the sailing route

LaneNum: The total number of lanes arranged in the ship

Length_each_lane: The length of each lane (in length unit)

OrderNum: The total number of transportation orders

SpotOrderNum: The number of spot orders

VehicleNum_each_Order: The number of vehicles in each order

VehicleLength_each_Order: The length of a vehicle in each order (in length unit)

Origin_each_Order: The origin port of each order

Destination_each_Order: The destination port of each order

ShiftingCost_each_Order: The cost of shifting a vehicle in each order

Revenue_each_SpotOrder: The revenue of executing each spot order
