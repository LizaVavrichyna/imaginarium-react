### IMAGINARIUM

## Overview
IMAGINARIUM is all about merging the power of storytelling with the magic of generative art. With the cutting-edge DALL-E model, users can craft visually stunning images that beautifully complement their narratives. These images are showcased as posts in the platform's vibrant feed, creating an immersive experience for users and viewers alike.

## Key Features
Generative Illustrations: Leverage the power of DALL-E to create unique and imaginative visuals that enhance your stories.
<img width="1792" alt="Screen Shot 2023-08-21 at 4 41 02 PM" src="https://github.com/LizaVavrichyna/imaginarium-react/assets/111198955/9b0dfd34-2dd9-4a13-ac87-bd923f740378">

Engaging Feed: Explore a dynamic feed where stories come to life through stunning visuals.
<img width="1146" alt="Screen Shot 2023-08-21 at 4 45 23 PM" src="https://github.com/LizaVavrichyna/imaginarium-react/assets/111198955/6b55efa5-dfba-4e54-8d46-54d0eb4c325f">


User Profiles: Customize your profile photo and name and showcase your portfolio of generative tales.
<img width="1792" alt="Screen Shot 2023-08-21 at 4 41 36 PM" src="https://github.com/LizaVavrichyna/imaginarium-react/assets/111198955/ecde007e-5217-4bab-b427-3b4253efde0b">

Convenient Navigation: Logged-in users can easily like and comment on post from other users, create new posts, edit posts, access their profile, and log out through the navigation bar.
<img width="1792" alt="Screen Shot 2023-08-21 at 4 42 22 PM" src="https://github.com/LizaVavrichyna/imaginarium-react/assets/111198955/d831b065-cfc1-4d97-9502-45609c78ab91">

## Installation
After cloning the project, install [React](https://www.freecodecamp.org/news/install-react-with-create-react-app/).

Start the development server:

<pre>
npm start
</pre>
The app should now be running locally at http://localhost:3000.

Install [JSON server](https://github.com/typicode/json-server).
Every time you want to run the application, you'll need to ensure that the API is running. Open a new terminal, in imaginarium-api directory start with:
<pre>

json-server -p 8088 database.json

</pre>

OpenAI API Integration
Generative Tales utilizes the OpenAI API to power the generative illustrations. To use the OpenAI API, you'll need an API key. If you don't have one, sign up for an account at openai.com and obtain your API key.
Remember to keep your API key secure and never share it publicly. The .env file is a good place to store sensitive information like API keys.
Create a .env file in the project root and add your [OpenAI API key](https://platform.openai.com/docs/api-reference/authentication)




