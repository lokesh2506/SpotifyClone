Spotify Clone (MERN Stack with Admin Panel)

This project is a Spotify clone developed using the MERN stack (MongoDB, Express, React, Node.js) with an admin panel for managing albums, songs, and playlists. The frontend is styled using Tailwind CSS.


Features:

User Role Management (RBAC): Users can listen to music by default, but the role needs to be changed to 'admin' to manage content.


Admin Panel:
Admin users can add albums, songs, and banners.
Admin can create and manage playlists.
Admin can view and manage the assets like thumbnails, song banners, and more.
User Experience: Non-admin users can access the music library and listen to songs.


Technologies Used:
MERN Stack: MongoDB, Express, React, Node.js
Tailwind CSS for frontend styling
RBAC (Role-Based Access Control) for user roles


Installation and Setup:

Step 1: Clone the repository

git clone <repository-url>
cd <project-folder>



Step 2: Run the Project

First, build the project to initialize the node modules:

--- npm run build   it will auto install the node modules
Then, start the project in development mode:

---npm run dev

The backend and frontend will now be running. You can access the application in your browser.

Frontend Assets:
All assets required for the frontend (thumbnails, song files, banners) are stored in the frontend/assets folder.

Admin Panel Instructions:

By default, a user is registered when they sign up. However, to access the admin functionalities (add albums, songs, create playlists, etc.), the user's role must be changed to admin by an existing admin.
Admin users can access additional options to manage the music library, albums, songs, and playlists.

Folder Structure:
Backend: Contains the Node.js server and API routes.
controllers/: Contains logic for handling album, song, and user management.
models/: Contains MongoDB models for users, songs, albums, and playlists.
routes/: API routes for handling user, album, song, and playlist operations.
Frontend: React frontend using Tailwind CSS for styling.
src/assets/: Folder containing thumbnails, banners, and music files.
src/components/: React components for displaying the UI.
src/pages/: Pages for different user views (e.g., home, album details, admin panel).

Conclusion:
This project mimics the core features of Spotify with an admin panel for managing music content. The use of MERN and Tailwind CSS ensures a robust, scalable, and highly customizable application.