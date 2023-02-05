# xeniya-travelsite 
### Multi-page static site HTML and CSS only.
### For a screen size of 1280px wide.

- The project built around common component code. I reused as much styling and code as possible (e.g. Destination Cards and Itinerary cards) by utilising inheritance, and @mixin, @use $variables, &-operator of SASS functionality.
- Used the BEM methodology for all class names.
- The layout of the site uses the Box Model, the CSS display property and CSS positioning including Flexbox. 
- Not used: floats.

Homepage:

![Screen Shot 2023-02-04 at 7 04 18 PM](https://user-images.githubusercontent.com/53381916/216794802-18497f81-675d-4868-a4e7-b6cf554e7848.png)

Destinations pages

![Screen Shot 2023-02-04 at 7 25 09 PM](https://user-images.githubusercontent.com/53381916/216795288-149269bc-58af-42de-8310-cc09a03553ab.png)
![Screen Shot 2023-02-04 at 7 25 21 PM](https://user-images.githubusercontent.com/53381916/216795286-7740a187-bd0a-4b24-9f9b-9c894f46a1a7.png)
![Screen Shot 2023-02-04 at 7 25 34 PM](https://user-images.githubusercontent.com/53381916/216795285-fa83810c-6dbd-4b2a-99b5-6e6da59c7f67.png)

Stylesheets (were provided by @moomance):

![Image 31-01-2023 at 20 54](https://user-images.githubusercontent.com/53381916/216794784-6dced87f-e5eb-4c34-89a7-c956a1bd330e.jpeg)
![Image 31-01-2023 at 20 54 (1)](https://user-images.githubusercontent.com/53381916/216794786-f43217d1-f6ef-43a5-8d82-f27b59e45cd6.jpeg)

Structure:

# The Travel Site has 4 Pages:
- Home Page
+ 3 Destinations Pages
  + Iceland
-- Greece
-- Hawaii
# The Home Page has 4 Sections:
- Navigation Bar: contains working links for each page:
  + Logo (links to the Home page)
-- Home
-- Iceland
-- Greece
-- Hawaii
  + The Navigation Bar is fixed to the top of the page
  + The currently active page is underlined
- Hero
- Recommendations
 + 3 Destination Cards: One card for each destination
Linked to the appropriate destination page (Iceland, Greece, Hawaii). 
Clicking anywhere on the card goes to the destination page. 
# The Destination Pages have 3 Sections:
- Navigation Bar (Same as Home Page)
- 3 Itinerary Cards for a 3 Day trip
  + Friday
-- Saturday
-- Sunday.
They have 3 Days of Itinerary activities including:
A title for the day of the week
4 Itinerary activities (e.g. Breakfast, Lunch, Dinner, Snorkeling)
# Footer (Same as Home Page)

