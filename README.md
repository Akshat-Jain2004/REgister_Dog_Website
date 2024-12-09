Random Dog Images and User Management
This project combines a fun way to browse random dog images with a robust user management system, including user registration and a list of registered users. The application uses Firebase for user authentication and Cloudinary for image storage, ensuring scalability and reliability.

Features:
Random Dog Images
Fetch random dog images from the Dog CEO API.
Navigate between images with "Next" and "Previous" buttons.
Maintain image history for seamless navigation.

User Management
Registration: Users can register with their details and upload a profile picture.
User List: Display a list of all registered users with their profile pictures, names, and additional details.

Technology Stack
Frontend
HTML5, CSS3, and JavaScript: For a responsive and interactive user interface.
Firebase SDK: Used for real-time database and authentication.

Backend Services
Firebase Firestore: For storing user details.
Cloudinary: For hosting and retrieving user profile pictures.
Dog CEO API: For fetching random dog images.

Pages Overview
1. Registration Page
Allows users to register by filling in their details and uploading a profile picture.
Utilizes Firebase Firestore to store user data and Cloudinary for image hosting.

2. User List Page
Displays all registered users in a card-style layout.
Clicking on a user card opens a modal with detailed information.
Data is fetched from Firebase Firestore, with images sourced from Cloudinary.

3. Random Dog Images
Displays random dog images with a visually appealing gradient background.
Includes navigation buttons to view the next and previous images.
Maintains an image history to navigate backward and forward seamlessly.


How to Run the Project
Clone the repository: git clone https://github.com/your-repo-name.git
cd your-repo-name

Install dependencies (if any) or open the HTML files directly in a browser.


Set up Firebase:
Go to Firebase Console and create a new project.
Replace the Firebase configuration in the firebaseConfig object within your script files.


Set up Cloudinary:
Create a Cloudinary account at cloudinary.com.
Note down your Cloud Name, API Key, and API Secret for image uploads.
Open the files in a browser or deploy them to a hosting platform like Netlify, Vercel, or Firebase Hosting.


Deployment
Ensure proper API keys and environment variables for Firebase and Cloudinary are configured before deployment.
Use Firebase Hosting for seamless integration with Firebase services.


Future Enhancements
Add user authentication with login/logout functionality.
Include image filters for specific dog breeds.
Optimize the UI for better performance on mobile devices
