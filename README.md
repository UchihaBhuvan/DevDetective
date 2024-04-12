# DevDetective

This user-friendly web application, built entirely with HTML, CSS, and JavaScript, allows you to effortlessly search and view public GitHub profiles.

Features:

Username Search: Enter a GitHub username in the search bar, and the app fetches the user's profile data.
Profile Overview: The app displays the following information about the user:
Profile Name
Number of Public Repositories
Follower Count
Following Count
Join Date (when the user created their GitHub account)
Profile Picture (if available)
Visually Appealing Design: The app employs CSS to create a clean and intuitive user interface, making the information easy to read and navigate.

Technical Breakdown:

HTML: Provides the basic structure of the web page, including the search bar, profile information sections, and image container.
CSS: Styles the HTML elements, defining the layout, colors, fonts, and overall visual presentation of the app.
JavaScript: Handles the core functionality:
Fetches user profile data from the GitHub API using techniques like Fetch API or XMLHttpRequest.
Parses the JSON response from the API to extract relevant information.
Dynamically updates the HTML content with the retrieved user data.
Optionally, error handling can be implemented to gracefully handle situations where the username is not found or the API request fails.


![Page](<Screenshot 2024-04-12 204706.png>)