KigaliQuest — Activities in Rwanda


PROJECT DESCRIPTION

KigaliQuest is a travel-themed web page that highlights top activities in Rwanda
— from gorilla trekking in Volcanoes National Park to sailing on Lake Kivu.
The project demonstrates core JavaScript DOM manipulation techniques through a
clean, responsive interface built with HTML, Tailwind CSS, and vanilla JavaScript.


FEATURES IMPLEMENTED

Dark / Light Mode
Toggle button in the navbar switches the entire page between light and dark
themes by dynamically adding and removing Tailwind CSS classes on the body,
navbar, cards, and footer.

Search and Filter
A search input filters the activity cards in real time as the user types.
Clicking the Search button or pressing Enter also triggers the filter.
Non-matching cards are hidden without a page reload.

Suggestion Tags
Predefined activity tags appear below the search input on focus. Clicking a
tag fills the input and filters the cards automatically.

Navigation Link Highlight
Clicking a navigation link marks it as active and removes the active state
from all other links, ensuring only one link is highlighted at a time.

Activity Cards
Four activity cards (Kigali City Tour, Gorilla Trekking, Nyungwe Canopy Walk,
Lake Kivu Sailing) each include a title, description, and a Discover More link.

Responsive Layout
The page adapts to different screen sizes using Tailwind's responsive grid
utilities.


WHAT THIS PROJECT DEMONSTRATES

- Selecting and traversing DOM elements using querySelector and querySelectorAll
- Handling user events with addEventListener (click, input, keydown, focus, blur)
- Dynamically modifying styles and classes with classList.toggle, add, and remove
- Showing and hiding elements by toggling the hidden class and display properties
- Capturing and reading user input from text fields in real time
- Filtering rendered content dynamically without any page refresh
- Building a theme-aware UI that responds to user interactions


TECH STACK

HTML5           - Page structure and semantic markup
Tailwind CSS    - Utility-first styling and responsive layout
JavaScript      - All DOM manipulation and interactivity


HOW TO RUN


1. Clone or download the repository
2. Place your image files in the root folder:
   kigali.jpg, mountain-gorilla-trekking.webp,
   nyungwe-canopy-walk.jpg, Lake-Kivu-Rwanda.jpg
3. Open index.html in any modern browser — no build step required