![OpenAI](https://i.imgur.com/Tq7N93x.png)
# OpenAI DALL-E 2 Image Generator
This is a web application that generates images from prompts using OpenAI's DALL-E2 API. The generated image, along with the prompt, image name, and Cloudinary image link, is then saved to a MongoDB database. The homepage displays a gallery of all the user-generated images.

# Features
* Image generation using OpenAI's DALL-E2 API
* MongoDB database to store generated images, prompts, image names, and Cloudinary image links
* Gallery page to display all user-generated images
* Responsive design optimized for desktop and mobile devices

# Technologies Used
* <ins>Tailwind CSS</ins> - A utility-first CSS framework for rapidly building custom designs.
* <ins>Vite</ins> - A fast build tool that leverages modern browser features for quicker development and production builds.
* <ins>React</ins> - A JavaScript library for building user interfaces.
* <ins>MongoDB</ins> - A document-oriented database that provides high performance, high availability, and automatic scaling.
* <ins>Express</ins> - A fast, unopinionated, minimalist web framework for Node.js.

# Getting Started
1. Clone this repository using `git clone https://github.com/fenn96/ai-app.git`
2. Install dependencies using `npm install`
3. Create a .env file in the client directory with the following environment variables:
```
VITE_BACKEND_URL=<Backend_URL>
```
4. Create a .env file in the server directory with the following environment variables:
```
OPENAI_API_KEY=<OpenAI_API_Key>
MONGODB_URL=<MongoDB_URL>
CLOUDINARY_CLOUD_NAME=<CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<CLOUDINARY_API_SECRET>
```
5. Start the backend using `npm start` in the server folder
6. Run the frontend using `npm run dev` in the client folder
7. Open http://localhost:5173 to view it in the browser

# How to Use
To generate an image, enter a prompt in the input field and click the generate button. The generated image will be displayed on the homepage along with its name, prompt, and Cloudinary image link.

To view all the user-generated images, go to the homepage. The homepage displays all the images that have been generated using the app, along with their names, prompts, and Cloudinary image links.
