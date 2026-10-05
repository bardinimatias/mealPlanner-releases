# MealPlanner

A simple desktop meal planner for Windows: keep your recipes and foods, plan your week's meals, see each day's calories and macros against your own targets, and get the week's grocery list.

## Download

**[Download the latest MealPlanner.exe](https://github.com/bardinimatias/mealPlanner-releases/releases/latest/download/MealPlanner.exe)**

Older versions are on the [Releases](https://github.com/bardinimatias/mealPlanner-releases/releases) page.

## First run

1. Save `MealPlanner.exe` somewhere you'll find it again, e.g. your Documents folder, and double-click it.
2. Windows may say **"Windows protected your PC"**. This appears because the app isn't code-signed yet. Click **More info**, then **Run anyway**. You only need to do this once per version.
3. The app opens. A green bar at the top offers to finish setting up. You can do it now or later (see below).

You can make a desktop shortcut: right-click `MealPlanner.exe` → **Show more options** → **Send to** → **Desktop (create shortcut)**.

## Food search (optional, free)

MealPlanner can look up foods and their nutrition in the USDA FoodData Central database. That needs a free API key:

1. Get one at **https://fdc.nal.usda.gov/api-key-signup** — it arrives by email.
2. In MealPlanner, open the **Settings** tab, paste the key, and click **Save**.

Without a key, everything else still works; you can enter foods by hand.

## Your data

Your recipes, foods, plans and settings are kept on your computer in `%LOCALAPPDATA%\MealPlanner`, separate from the app itself. To update, just download the new `MealPlanner.exe` and use it instead of the old one — your data stays.
