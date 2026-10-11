# Meal Prep Planner

## The problem
I would get flashes of inspiration for what meals to prep for the week and I write down the ingredients I would need in my notes app.
However, when it came down to actually sourcing and preparing the ingredients, I would get overwhelmed by the thought of the time-sink and fail to get started.

## Who uses it and where
I typically jot down notes on what to prepare whenever they come to mind, however I forget to reopen my notes later in the week.
The Notes app on my Google Pixel is nice, but I get distracted and I am quite forgetful so it'd be nice to have an app to remind me to go buy my ingredients.

## Core actions
1. Save a recipe and its ingredients
2. Pick recipes for the week
3. Generate a merged grocery list and check off items

## Data it stores
- Recipe: name, servings, total prep time, ingredients (name, amount, unit)
- Meal plan: week, recipes picked, servings per recipe

## Calculated 
- Adjusted ingredient amount = recipe amount x plan servings / recipe servings
- Grocery list (built from the meal plan each time)

## Versions Plans
- v0: Save recipes (name, servings, total prep time, ingredients with amounts). Pick recipes for the week. Generate one merged grocery list. Check items off.
- v1: Phone-friendly UI, ingredient costs, weekly cost + prep time totals, scale servings
- v2: Sunday reminder, “haven’t made in a while” suggestions, store log