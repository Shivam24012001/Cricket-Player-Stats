# **Cricket Player Stats Lookup Using XLOOKUP in Google Sheets** 

## **📌 Project Overview**
This project demonstrates the use of **XLOOKUP** in Google Sheets to retrieve player statistics, match details, and awards received by various cricket players. The dataset consists of multiple records detailing matches played and awards won, and the queries provided in the **"Questions"** tab are solved using **XLOOKUP**.


---

## **📊 Key Features** 
✅ **Player Lookup** – Fetch details of matches played and awards received by individual players.  
✅ **Dynamic Searching** – Use **XLOOKUP** to search for player statistics efficiently.  
✅ **Error Handling** – Handle missing values with default outputs to avoid errors.  
✅ **Flexible Matching** – Implement **XLOOKUP** options such as exact matches, approximate matches, and wildcard searches.  
✅ **Optimized Data Retrieval** – Utilize **search modes** for better performance.  

---

## **📌 XLOOKUP Formula Explanation**
The project primarily uses the **XLOOKUP** function with different parameters:

```excel
=XLOOKUP(search_key, lookup_range, result_range, [missing_value], [match_mode], [search_mode])
```

### **🔹 Breakdown of Parameters:**
- `search_key` – The player name or match ID to search for.  
- `lookup_range` – The column or row where the search is performed.  
- `result_range` – The corresponding column or row from which the result is fetched.  
- `missing_value` – Default value if no match is found.  
- `match_mode` – Determines whether to find an exact match, an approximate match, or use wildcards.  
- `search_mode` – Specifies the order in which Google Sheets searches for matches.  


---

## **📌 Example Queries Solved**
📍 Retrieve the number of matches played by a specific player.  
📍 Find the awards won by a player based on their name.  
📍 Handle missing player records by returning a default message.  
📍 Use wildcard searches to find players with partial names. 
