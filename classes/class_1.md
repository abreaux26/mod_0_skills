# Class:
Kitchen

### Attributes:
* is_meal_ready (Boolean)
* foods_in_fridge (Array)
* clean_utensils (Array)
* dirty_utensils (Array)

### Methods:
* store_food (adds to foods_in_fridge array)
* prepare_food (removes food form foods_in_fridge array and sets is_meal_ready to false)
* cook_food (sets is_meal_ready to true, removes utensils from clean_utensils array, and adds those utensils to dirty_utensils array)
* wash_dish (passes in dish to wash and removes utensil from dirty_utensils array and adds to clean_utensils array)
