# Nextjs jq meme generator

Create a gallery of memes using NextJS that renders posts from reddit.com/r/memes.

<img width="853" alt="image" src="https://github.com/Rohan10027/nextjs-jq-meme-generator/assets/90006085/bd7f3da9-3266-45c0-acd0-7b5941d0f9df">

# Instructions
• You can use Reddit's API to fetch the thumbnail and URL for each post.
• You can use the Photoswipe library to implement the gallery. Clicking on a thumbnail in the gallery should display the image in its full resolution.
• Also, the gallery should scroll infinitely. You can fetch more entries using the after attribute (as the user scrolls down).
Application Features:

# Setting up NextJS Project:
Begin by setting up a new NextJS project using create-next-app or any preferred method.

# Reddit API Integration:
Use Reddit's API to fetch posts from the "memes" subreddit. You may need to obtain API credentials from Reddit if required.

# Fetching Initial Posts:
Use the Reddit API to fetch the initial set of posts from https://www.reddit.com/r/memes.json. Extract relevant information such as post title, thumbnail, and URL.

# Displaying Thumbnails:
Display the fetched post thumbnails in a grid on the main page. You can use NextJS's Image component or a similar solution for efficient image loading.

# Infinite Scrolling:
Implement infinite scrolling so that as the user scrolls down, more entries are fetched. Use the after attribute in the Reddit API to paginate through the posts.

# Optimizing Image Loading:
Optimize image loading by using lazy loading techniques. Load images only when they are about to enter the viewport to improve performance.

# Error Handling:
Implement error handling for API requests. Handle cases where the Reddit API might return errors or if there are issues loading images.

# Responsive Design:
Ensure that the gallery is responsive to different screen sizes. Test on various devices and consider using responsive design techniques.

# Documentation:
Document the code and provide clear instructions on how to run the application. Include any necessary setup steps and dependencies.

# Deployment:
Deploy the NextJS application to a hosting platform of your choice. Ensure that the deployed version works as expected.

# Future Improvements:
Consider potential future improvements such as caching mechanisms to improve performance, adding search functionality, or incorporating user authentication for personalized experiences.
Check out the website live on (https://rebrand.ly/rohancvbn/vercel-app)


# Start Application on localhost
npm run dev

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the https://rebrand.ly/rohancvbn/vercel-app from the creators of Next.js.
