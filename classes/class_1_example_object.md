# instance:
Kitchen

### attributes:
is_meal_ready (Boolean): false
foods_in_fridge (Array): ["veggies", "steak", "milk"]
clean_utensils (Array): ["spatula", "tongs", "pan", "cutting board", "knife"]
dirty_utensils (Array): []

### methods:
store_food: foods_in_fridge = ["veggies", "steak", "milk"]
prepare_food: foods_in_fridge = ["milk"]; is_meal_ready = false
cook_food: is_meal_ready = true; clean_utensils = ["spatula"]; dirty_utensils = ["tongs", "pan", "cutting board", "knife"]
wash_dish("tongs"): clean_utensils = ["spatula", "tongs"]; dirty_utensils = ["pan", "cutting board", "knife"]
