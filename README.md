Chef's Menu Manager

Project Overview

Chef's Menu Manager is a React Native application developed for the MAST5112 Portfolio of Evidence.
The application helps a restaurant chef manage menu items digitally. It allows the chef to add, view, edit, delete, search, and filter dishes. It also provides useful menu statistics that update automatically whenever the menu changes.

Features
Add Menu Items
The chef can enter:
•	Dish name
•	Description
•	Course
•	Price
Available courses are:
•	Starter
•	Main Course
•	Dessert

Edit Menu Items
An existing menu item can be opened in the form and updated. The saved changes are immediately reflected in the menu list and statistics.
Delete Menu Items
The chef can delete an existing menu item. A confirmation message is displayed before the item is permanently removed.

Search and Filter
The chef can:
•	Search for a menu item by dish name
•	Filter menu items by course
•	Combine searching and filtering

Menu Statistics
The application displays:
•	Total number of menu items
•	Average price of all menu items
•	Number of Starters
•	Number of Main Courses
•	Number of Desserts
The statistics update automatically when an item is added, edited, or deleted.
Validation and Feedback

The application:
•	Checks that all required fields are completed
•	Ensures that the price is a valid number greater than zero
•	Highlights invalid fields
•	Displays appropriate error messages
•	Displays confirmation messages after adding, editing, or deleting an item
•	Displays a suitable message when the menu is empty
•	Displays a suitable message when no items match a search or filter

Application Screens
The application contains two main screens.

Home Screen
The Home screen contains:
•	Menu statistics
•	Search field
•	Course filters
•	Clear Search and Filter button
•	Menu-item list
•	Edit and Delete buttons
•	Add Menu Item button

Add/Edit Screen
The form screen allows the chef to:
•	Add a new menu item
•	Edit an existing menu item
•	Select a course
•	Save changes
•	Cancel and return to the Home screen

Technologies Used
•	React Native
•	JavaScript
•	React
•	Expo Snack
•	React Native components, including:
o	View
o	Text
o	TextInput
o	TouchableOpacity
o	FlatList
o	ScrollView
o	KeyboardAvoidingView
o	StyleSheet

Interface Design
The application uses a simple and consistent colour palette:
•	Light grey for the main background
•	White for cards and input fields
•	Dark grey for readable text
•	Dark green for primary actions and successful feedback
•	Red for validation errors and delete actions

Changelog
The Final PoE version extends the Part 2 application by adding:
•	Editing and updating menu items
•	Deleting menu items
•	Delete confirmation
•	Searching by dish name
•	Filtering by course
•	Clearing search and filter values
•	Menu statistics
•	Two-screen navigation
•	Reusable components and functions
•	Improved code organisation
•	Improved validation and user feedback
•	A more polished and consistent interface
In Part 1, a Picker component was planned for selecting a course. During development, course-selection buttons were used instead. These buttons clearly display all available courses and provide immediate visual feedback when a course is selected

How to Use the Application
1.	Select Add Menu Item.
2.	Enter the dish name and description.
3.	Select a course.
4.	Enter a valid price.
5.	Select Save Menu Item.
6.	View the new item on the Home screen.
7.	Use Edit Item to change its information.
8.	Use Delete Item to remove it.
9.	Enter a dish name in the search field to find an item.
10.	Select a course filter to display items from that course.
11.	Select Clear Search and Filter to display the complete menu
    
Testing
The application was tested by:
•	Submitting an empty form
•	Entering an invalid price
•	Adding items from each course
•	Editing existing menu items
•	Deleting menu items
•	Searching by full and partial dish names
•	Filtering by each course
•	Combining search and filtering
•	Clearing search and filters
•	Checking that statistics update after every change
•	Checking the layout on Expo Snack's Web and mobile previews

Reference List

GeeksforGeeks ,2025. How to Implement Form Validation in React Native? [online] Available at:< https://www.geeksforgeeks.org/mobile-computing/how-to-implement-form-validation-in-react-native/> Accessed [5 September 2026].

GeeksforGeeks 2025, React Native FlatList Component. [online] Available at: < https://www.geeksforgeeks.org/react-native/react-native-flatlist-component/  > Accessed [5 September 2026].
Green Color Codes ,2026. Green Color Codes. [online] Available at: <https://html-color.codes/green > Accessed [6 September 2026].

Grey Color Codes, 2026.Grey Color Codes. [online] Available at: <https://html-color.codes/grey > Accessed [6 September 2026].

JavaScript Mastery ,2026. React Native Full Course 2026 | Build, Publish and Monetize a Full Stack Mobile App to App Store. [video online] Available at: <https://www.youtube.com/watch?v=4nVoLX2taFg > Accessed [1 September 2026].

Kapadi, A,2025. How to Build a Dynamic Pricing Table in React Native with Minimal Code. [online] Available at: <https://medium.com/@amolakapadi/how-to-build-a-dynamic-pricing-table-in-react-native-with-minimal-code-1e600ad86fa7 > Accessed [5 September 2026].

Magaudini, A, 2026.Poe App, MAST5112, Mobile App Scripting Accessed [5 November 2026]

Magaudini, A, 2026.Sample App, MAST5112, Mobile App Scripting Accessed [4 September 2026]

MDN Web Docs, 2025.Number. isFinite() – JavaScript. [online] Available at: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isFinite > Accessed [5 September 2026].

React Native,2026. Handling Text Input. [online]. Available at: <https://reactnative.dev/docs/handling-text-input> (Accessed: 1 November 2026).

React Native, 2026.Height and Width. [online] Available at: <https://reactnative.dev/docs/height-and-width> Accessed [5 September 2026].

React Native, 2026.Layout with Flexbox. [online] Available at:< https://reactnative.dev/docs/flexbox > Accessed [5 September 2026].

React Native,2026. Using a ScrollView. [online]. Available at: <https://reactnative.dev/docs/using-a-scrollview> (Accessed: 2 November 2026).

Red Color Codes 2026, Red Color Codes. [online] Available at :< https://html-color.codes/red>
Accessed [6 September 2026].




