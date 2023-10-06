Step 1:
Within SkewedNavbar.js, add a "className" 
attribute to the <ul> tag. Update Sidebar.css.

Step 2:
- In the App.js file, make adjustments
to the props passed to the SkewedNavbar component.
- Additionally, enhance the existing useEffect
function in App.js, which updates the chart,
so that it filters habits according to the
selected category.

Step 3:
- In CategoryDropdown.js define an array
of default categories.
- First map over defaultCategories, which contains
the default categories you want to display.
- For each default category, create a button 
element with the category name as the label.
- Use the onClick event handler to call 
onCategorySelect(category) when a category 
is clicked, passing the category name
as an argument.
- Apply a CSS class (selected) to the button
if it matches the selectedCategory.
