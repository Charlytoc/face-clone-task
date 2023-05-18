# Welcome to the Facebook friends clone project

This are the steps to succesful develop the project:

## Clone the repository:

- Open a terminal or command prompt.
- Navigate to the directory where you want to clone the repository.
- Run the following command:

```
git clone <repository_url>
```

Replace <repository_url> with the URL of the repository.


## Get inside the cloned folder:

In the terminal or command prompt, navigate to the cloned repository's folder using the cd command:
```
cd <repository_folder>
```

Replace <repository_folder> with the name of the cloned repository's folder.

## Install dependencies:

> Make sure you have Node.js and npm (Node Package Manager) installed on your machine.
Run the following command to install the project dependencies:
```
npm install
```

## Run the project:

Use the following command to start the development server:
```
npm run dev
```

## Access the app:

- Open a web browser and go to localhost:5173. This is the default address where the app will be served.
- Now that the initial setup is complete, let's proceed with creating the app with two views: a view for users and a view for each user.

## Create the Users (plural) View:

- Open your code editor or integrated development environment (IDE).
- Navigate to the project's source code directory.
- Look for the file responsible for creating the Users View. It could be named something like Users.js or Users.jsx.
- Inside that file, write the necessary code to fetch the user data from the JSON Placeholder API: https://jsonplaceholder.typicode.com/users.
- Display the user information retrieved from the API on the Users View.
- Add a link or button for each user to navigate to their individual view.

## Create the User (singular) biography + post view:

- In the same source code directory, find or create a file for the User View, such as User.js or User.jsx.
- Implement the code to fetch the user's posts from the JSON Placeholder API: https://jsonplaceholder.typicode.com/posts?userId=<user_id>.
- Replace <user_id> with the actual ID of the user whose posts you want to retrieve.
- Display the user's information and their associated posts on the User View.

## Connect the Users View and User View:

- In the Users View, make sure the links or buttons you added in Step 6 are set up to navigate to the corresponding User View for each user.
- Pass the necessary data (e.g., user ID) from the Users View to the User View when navigating to it.
- In the User View, use the received data (e.g., user ID) to fetch and display the correct user's information and posts.


## Point and evaluation criteria

- Create a Facebook friends clone app with two views: a Users View and a User View. (10 points)
- Fetch user data from the JSON Placeholder API using Axios. (15 points)
- Utilize React's useState hook to manage state within the components. (15 points)
- Use React's useEffect hook to handle side effects such as data fetching. (10 points)
- Display user information on the Users View and individual user information with their associated posts on the User View. (20 points)
- Enable navigation from the Users View to the User View for each user. (10 points)
- Ensure that the User View fetches and displays the correct user's information and posts based on the selected user. (20 points)

Total: **100** **point**.