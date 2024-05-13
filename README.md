# ghw-crud-food
GHW Data Building a CRUD app

Application needs:
- Meal plan
    - different recipes we want to cook throughout the week, month, year, etc
    - add/update/delete meal
    - meal id: reciepe name
    - serving size: num of people the recipe feeds
    - carbs (g)
    - fat (g)
    - protein (g)
    - ingredients: dictionary
    - reciepe: text/link

- Schedule Plan
    - our plans throughout the week, month, year, etc
    - can integrate entire schedule - integrating any plans you have that will affect your eating for the next week
    - add/update/delete our plans
    - eating_location: ['at home','not at home']
    - plan id: what the plan is/text ['work lunch','dinner at mom's house','party at john's',' movie night w/ roommate','studying for finals'] 
    - date: month/date/year
    - time: hour:minute ['breakfast','lunch','dinner']

- Grocery List
    - what foods we need to buy for our meal plan
    - based off of the meals in the next 2 weeks
    - able to add/update/delete individual items if you need more seasoning or already have some of the food at home
    - count: integer (number of grocery items needed)
    - grocery id: text (name of the grocery item)