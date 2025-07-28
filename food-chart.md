-------
title:weekly food chart
layout: spark
-------

| Day       | Breakfast         | Lunch            | Dinner         |
|-----------|-------------------|------------------|----------------|
| Monday    | Oatmeal & fruit   | Grilled chicken  | Veggie stir fry|
| Tuesday   | Eggs & toast      | Pasta salad      | Tacos          |
| Wednesday | Smoothie bowl     | Tuna sandwich    | Rice & curry   |

<spark-chart type="bar" x="Day" y="Calories">
[
  { "Day": "Mon", "Calories": 1800 },
  { "Day": "Tue", "Calories": 1900 },
  { "Day": "Wed", "Calories": 1700 }
]
</spark-chart>
