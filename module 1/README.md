Angular Module and Controller:
LunchCheck is the Angular module.
LunchCheckController is where the logic is implemented, which is injected with $scope.
Controller Functionality:
checkIfTooMuch() is the function that runs when the button is clicked.
If the input is empty (either empty string or just spaces), the message "Please enter data first" is shown.
Otherwise, the input is split by commas and the filter() method removes any empty or space-only items from the list.
If the number of valid items is less than or equal to 3, "Enjoy!" is displayed. If more than 3 items are entered, "Too much!" is shown.
CSS Styling:
The green and red classes are applied dynamically based on the message to style both the input border and message color.
