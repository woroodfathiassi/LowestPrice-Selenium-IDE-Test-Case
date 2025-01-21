# LowestPrice-Selenium-IDE-Test-Case  

This repository contains the Selenium IDE test case **"LowestPrice"**, designed to automate the process of finding and validating hotel prices on Skyscanner. The test ensures that hotel prices are displayed in ascending order and reports any inconsistencies.

---

## Features  

- Navigates to the Skyscanner website and accesses the Hotels section.  
- Performs a search for hotels in New York.  
- Iterates through the search results to verify that hotel prices are displayed in ascending order.  
- Logs errors and halts the test if the price order condition is violated.  

---

## Automation Testing with Selenium  

Using **Selenium** for automation testing, we verified that the hotel price filtering functionality on Skyscanner works correctly. Below are the steps performed:  

1. **Navigating to Skyscanner:**  
   Selenium was used to open the Skyscanner website and access the Hotels section.  

2. **Performing a Search:**  
   A search was conducted for hotels in New York City as part of the test scenario.  

3. **Applying the Price Filter:**  
   The price filter was applied to verify that the displayed results adhered to the selected price range or order.  

4. **Validating Price Order:**  
   - The test confirmed that the search results displayed hotel prices in ascending order (from lowest to highest) when this order was selected.  
   - Prices were extracted from the search results and checked programmatically to ensure they were sorted correctly.  

5. **Error Handling:**  
   If any inconsistency in price order was detected, the issue was logged, and the test execution was halted.  

---

### Results  

The automation test confirmed that the price filtering functionality works accurately, ensuring that hotel prices are displayed as expected. Any discrepancies are promptly detected through the automation process, guaranteeing an improved user experience.  

![Test Results Screenshot](images/results-screenshot.png)  
