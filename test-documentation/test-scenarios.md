# Test Scenarios - Ksisters Website

## Search Functionality
### Input Testing
* Valid input ("Cream", "Gels", "Patches")
* Empty input
* Spaces only input
* Special characters (!@#$%)
* Numbers (1, 2, 10, 50, 55, 100, 123)
* Emoji (🔥)
* Different language input ("Крем", "Гель")

### Processing Testing
* Case sensitivity (cream vs CREAM)
* Partial match (cre -> cream)
* Typo handling (creaam, creamm)
* Consistency of similar typos (creaam vs creammm)

### Output Testing
* Relevant results for valid input
* No results case
* Correct number of results
* System behavior for empty input (full catalog displayed)

### UI / UX Testing
* "Results for" label display
* Behavior with empty query (UI vs keyboard)
* Submit empty input using `Enter` key
* Clarity of results page
* Consistency of search UI


