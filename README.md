# TO DO

# Recap
First, Make sure you npm install everything and then launch the empty page. (npm run dev)

Then, When you do : "npx remotion render videos/index.ts Demo out.mp4", it will create the video based on the Composition file and download it locally in the root folder. (You may need FFMPEG install and in a path variable to have this)

You can also do "npx remotion preview videos/index.ts" to see the video preview in the browser

# What i would like to do:
1- On the click of the button from index file, Do the same and download the video locally (So not to build the video on the build, but when needed)

# To do so:
Using the server side rendering from remotion
https://www.remotion.dev/docs/ssr

As well as the server side capabilities from nextjs
https://nextjs.org/docs/basic-features/data-fetching/overview

# Is this possible ? How to do it easily -> See content of files "/pages/index.js" and "/pages/api/render-video.js"
