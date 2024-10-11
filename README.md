# Github-ID-finder
The GitHub ID Finder is a simple and efficient web application that allows users to search for and retrieve basic information about any GitHub profile using just the username. The app is built using HTML, CSS, and JavaScript and integrates the GitHub API to fetch and display the relevant data.

Key Features:
1. User-Friendly Interface: The website features a clean and intuitive design, making it easy for users to input a GitHub username and receive the corresponding profile information.
2. Real-Time GitHub Profile Search: Users can enter a GitHub username, and the application will query the GitHub API to fetch details such as the user's GitHub ID, avatar, public repositories count, and follower count.
3. Error Handling: If an invalid or nonexistent GitHub username is entered, the application will display an appropriate error message.
4. Responsive Design: The website is fully responsive, ensuring an optimal user experience on both mobile and desktop devices.
5. Dark-Light mode feature: Using javascript website has also feature for dark and light mode.
   
Technologies Used:
HTML: For structuring the web page and creating input forms.
CSS: To style the page, ensuring a clean, visually appealing layout.
JavaScript: To handle user input, make API requests, and dynamically update the web page with the fetched data.
GitHub API: Used to fetch details about a user’s GitHub profile by making an HTTP request using the username.

How It Works:
1.The user enters a GitHub username in the search bar.
2.Upon clicking the "Search" button, a request is made to the GitHub API to retrieve information about the specified user.
3.The application displays the user’s GitHub ID, along with additional details like their avatar, number of repositories, and followers.
4.If the user does not exist, an error message is shown.
