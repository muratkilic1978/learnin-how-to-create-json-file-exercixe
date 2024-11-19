# Exercise: Create a JSON File for Football Clubs

---

## **Objective:**
Learn how to create a well-structured JSON file to store information about football clubs and validate it using an online JSON validator.

---

## **Scenario:**
You are tasked with creating a JSON file that stores information about different football clubs. Each football club should have specific details, including its name, stadium, capacity, and other attributes.

---

## **Requirements:**
Each football club in your JSON file should include the following information:
1. **Club Name** (string): The name of the football club.
2. **Stadium Name** (string): The name of the stadium where the club plays.
3. **Capacity** (number): The seating capacity of the stadium.
4. **Built Year** (string): The date when the stadium was built, in the format `YYYY-MM-DD`.
5. **Image Path** (string): The relative path to an image of the stadium.
6. **Football Field Dimensions** (object): Include:
   - **Length** (number): The length of the football field in meters.
   - **Width** (number): The width of the football field in meters.
   - **Unit** (string): The unit of measurement (e.g., "meters").

---

## **Task:**
Based on the given structure, create a JSON file for **two football clubs**. Use the following information as input:

1. **Club 1:**
   - Club Name: Manchester United
   - Stadium Name: Old Trafford
   - Capacity: 74879
   - Built Year: 1910-02-19
   - Image Path: `img/old-trafford.jpg`
   - Football Field:
     - Length: 105
     - Width: 68
     - Unit: meters

2. **Club 2:**
   - Club Name: Paris Saint-Germain
   - Stadium Name: Parc des Princes
   - Capacity: 47929
   - Built Year: 1972-07-25
   - Image Path: `img/parc-des-princes.jpg`
   - Football Field:
     - Length: 105
     - Width: 68
     - Unit: meters

---

## **Validation:**
Once you have created the JSON file, use [JSONLint](https://jsonlint.com/) to validate that your JSON file is correctly formatted. Copy and paste your JSON into the tool and click "Validate JSON."

---

## **Challenge (Optional):**
After completing the above exercise, try adding **two more football clubs** of your choice using the same structure. Be sure to include all the required details, such as club name, stadium name, capacity, built year, image path, and football field dimensions. Validate your extended JSON file again to ensure it is correct. 

---
