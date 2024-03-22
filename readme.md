
# Instagram Clone 

This is a project aimed at replicating the basic functionalities of Instagram using Node.js, Express.js, and MongoDB.

## Preview 

### Login & Register 🔐

![loginregister-ezgif com-video-to-gif-converter](https://github.com/ind-abhishek/instaclone/assets/101976775/87befa59-05fc-4648-ad2f-dde0c0d82716)


Users can sign up for a new account or log in securely using their username and password.

### Feed 📰
![whole-ezgif com-video-to-gif-converter](https://github.com/ind-abhishek/instaclone/assets/101976775/0c9fdf41-9712-46a8-94ef-87dc58f16be1)

The feed displays posts from users that the logged-in user follows, along with stories from other users.

### Profile & Edit 🖋️

![profile-editable-ezgif com-video-to-gif-converter](https://github.com/ind-abhishek/instaclone/assets/101976775/00214226-d32f-4c61-8219-f16b59c069cf)


Users have their own profile page where they can view their posts and edit their profile information.

### Add Post 📝

![addpost-ezgif com-video-to-gif-converter](https://github.com/ind-abhishek/instaclone/assets/101976775/f2bba7cc-f253-4cad-997f-ee5cfcb6b56d)


Users can create new posts or stories by uploading images and adding captions.

## Features ✨

- **User Authentication**: Users can sign up, log in, and log out securely using Passport.js and local authentication strategy.
- **Posting**: Users can create posts and stories, with the option to upload images. Posts and stories are associated with the user who created them.
- **Feed**: Users can view a feed of posts from users they follow, as well as stories from other users.
- **Profile**: Each user has a profile page where they can view their own posts, edit their profile information, and view the posts of other users.
- **Interactions**: Users can like posts, follow other users, and save posts.

## Installation 🛠️

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone [https://github.com/ind-abhishek/insta.git]
   ```

2. Install dependencies:

   ```bash
   cd instagram-clone
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Define the following environment variables:

     ```
     PORT=3000
     MONGODB_URI=mongodb://localhost:27017/instagram
     SESSION_SECRET=your_session_secret
     ```

4. Run the application:

   ```bash
   npm start
   ```

## Usage 🚀

Once the application is running, you can access it at `http://localhost:3000` in your web browser. Here are some basic usage guidelines:

- **Sign Up**: Create a new account by providing a username, email, and password.
- **Log In**: Log in with your username and password.
- **Posting**: Create new posts or stories by navigating to the "Upload" page.
- **Interactions**: Like posts, follow other users, and save posts to view them later.
- **Exploring**: Use the search feature to find other users and view their profiles.

## Credits 💻

This project was developed by [Abhsihek Sharma](https://github.com/ind-abhishek).
