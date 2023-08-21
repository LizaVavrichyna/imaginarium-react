### IMAGINARIUM

## Overview
IMAGINARIUM is all about merging the power of storytelling with the magic of generative art. With the cutting-edge DALL-E model, users can craft visually stunning images that beautifully complement their narratives. These images are showcased as posts in the platform's vibrant feed, creating an immersive experience for users and viewers alike.

## Key Features
Generative Illustrations: Leverage the power of DALL-E to create unique and imaginative visuals that enhance your stories.

Engaging Feed: Explore a dynamic feed where stories come to life through stunning visuals.

User Profiles: Customize your profile photo and name and showcase your portfolio of generative tales.

Convenient Navigation: Logged-in users can easily create new posts, edit posts, access their profile, like and comment on post from other users and log out through the navigation bar.

## Installation
After cloning the project, install [React](https://www.freecodecamp.org/news/install-react-with-create-react-app/).

To run the project:

<pre>
npm start
</pre>
The app should now be running locally at http://localhost:3000.

OpenAI API Integration
Generative Tales utilizes the OpenAI API to power the generative illustrations. To use the OpenAI API, you'll need an API key. If you don't have one, sign up for an account at openai.com and obtain your API key.
Remember to keep your API key secure and never share it publicly. The .env file is a good place to store sensitive information like API keys.
Create a .env file in the project root and add your [OpenAI API key](https://platform.openai.com/docs/api-reference/authentication):


Start the development server:

<pre>

npm start

</pre>


Every time you want to work on your application, you'll need to ensure that the API is running. Open a new terminal, in imaginarium-api directory start with:
<pre>

json-server -p 8088 database.json

</pre>
