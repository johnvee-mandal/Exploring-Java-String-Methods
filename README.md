# Exploring Java String Methods


## 1. `length()`

* **Prediction:** Returns the number of characters in the string, including spaces and special characters.
* **Observation:** The method returned the exact count of characters in the string.


## 2. `charAt()`

* **Prediction:** Returns the character located at the specified index (starting from 0).
* **Observation:** The returned character matched the one located at the given index.


## 3. `substring()`

* **Prediction:** Extracts part of the string starting from a given index, optionally ending before another index.
* **Observation:** Returned only the part of the string between the specified indexes.


## 4. `toUpperCase()` and `toLowerCase()`

* **Prediction:** Converts all characters in the string to uppercase or lowercase.
* **Observation:** All letters were converted to the desired case; non-letter characters were unchanged.


## 5. `indexOf()`

* **Prediction:** Returns the position (index) of the first occurrence of a specified character or substring, or -1 if not found.
* **Observation:** Returned the index of the first match, starting from the beginning of the string.



## 6. `equals()` and `equalsIgnoreCase()`

* **Prediction:** `equals()` compares strings exactly, including case; `equalsIgnoreCase()` ignores case differences.
* **Observation:** `equals()` returned false if case didn’t match, while `equalsIgnoreCase()` returned true when the only difference was letter case.




## 7. `replace()`

* **Prediction:** Replaces all occurrences of a specified character or substring with another.
* **Observation:** All matching parts of the string were replaced with the new value.




## 8. `trim()`

* **Prediction:** Removes spaces from the start and end of the string.
* **Observation:** Leading and trailing spaces were removed, but spaces in the middle remained.



