# Github-Profile-Search
The provided code is for a web application project that allows users to search for GitHub profiles and view detailed information about the users they find. Here are the key details about this project:

# User Interface:
The project has a user-friendly interface with the following main components:

# Search Bar:
Users can input a GitHub username to search for a specific user.
Profile Display: Once a user is found, their GitHub profile information is displayed, including their avatar, name, username, bio, repository count, followers, following, location, website, Twitter handle, and company.
Dark Mode:
The project supports both light and dark modes. Users can toggle between these modes using a dedicated button. The appearance of the webpage, including colors and icons, changes dynamically when switching between modes.

# API Integration:
The application utilizes the GitHub API to fetch user data based on the username entered in the search bar. It makes an asynchronous API call to retrieve user information and then updates the UI with the fetched data.

# Initialization: 
When the webpage loads, it initializes the UI and checks localStorage to determine the initial mode (dark or light). Additionally, it fetches and displays the GitHub profile of a default user ("jagmohan123") as an initial example. This project provides a simple and visually appealing way for users to search for and view GitHub profiles while offering a choice between light and dark modes for a personalized browsing experience.
