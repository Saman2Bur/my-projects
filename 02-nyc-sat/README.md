# NYC SAT Analysis

This project analyzes SAT results from NYC public schools to explore math performance, overall scores, and borough-level differences.

## Project Tasks
1. **Best math results**  
   - Define the best math results as at least 80% of the maximum possible math score (800), i.e. ≥ 640.  
   - Save the results in a DataFrame called `best_math_schools`.  
   - Include `school_name` and `average_math`, sorted by `average_math` in descending order.

2. **Top 10 performing schools**  
   - Create a new column `total_SAT = average_math + average_reading + average_writing`.  
   - Save the results in a DataFrame called `top_10_schools`.  
   - Include `school_name` and `total_SAT`, sorted by `total_SAT` in descending order.  
   - Keep the top 10 schools.

3. **Borough with largest standard deviation**  
   - Group schools by `borough` and calculate:  
     - `num_schools` — number of schools  
     - `average_SAT` — mean of `total_SAT`  
     - `std_SAT` — standard deviation of `total_SAT`  
   - Save the borough with the highest `std_SAT` in a DataFrame called `largest_std_dev`.  
   - The DataFrame should contain one row with columns: `borough`, `num_schools`, `average_SAT`, `std_SAT`.  
   - Round all numeric values to two decimal places.
