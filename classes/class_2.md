# class:
Server

### attributes:
name (String)
tip (Float)
table_number (Integer)
num_of_guests (Integer)
is_food_delivered (Boolean)
order (Hash)

### methods:
table_info (sets num_of_guests at table and sets table_number)
take_order (adds to order hash, sets is_food_delivered to false)
deliver_order (sets is_food_delivered to true)
check_on_table (increases tip amount)
