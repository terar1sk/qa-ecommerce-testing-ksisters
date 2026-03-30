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


## Registration Functionality
### Input Testing
* Valid data (name, email, password)
* Invalid email formats (test@test, test@.com, test@site..com)
* Very long name (100+ characters)
* Very long email input
* Password with only spaces
* Password with leading/trailing spaces
* Special characters in name (<script>, @@@@@)
* Empty required fields

### Validation Testing
* Email validation message
* Password validation rules (min length)
* Handling of spaces-only input
* Proper error messages display

### Security Testing
* Script injection input (<script>alert(1)</script>)
* Special characters handling
* Input sanitization

### UI / UX Testing
* Error messages readability
* Field validation feedback
* Form behavior after submission


## Cart Functionality
### Basic Actions
* Add product to cart
* Remove product from cart
* Increase/decrease quantity
* Add multiple products

### Edge Cases
* Remove last item from cart
* Empty cart behavior
* Rapid clicks on add/remove buttons

### Calculation Testing
* Correct subtotal calculation
* Shipping cost calculation
* Total price calculation
* Cart state after item removal

### State Management
* Cart update without page refresh
* Cart state after refresh
* Consistency between UI and actual data

### UI / UX Testing
* Display of "0 items" state
* Checkout button behavior
* Cart summary visibility


## Product Page Functionality
### Basic Functionality
* Open product page
* Display product details
* Add product to cart

### API / Data Testing
* Product data loading
* Handling of missing data
* Response status codes

### Error Handling
* Behavior when API returns 404
* Missing static content (SEO text)

### UI / UX Testing
* Product layout consistency
* Image loading
* Button functionality