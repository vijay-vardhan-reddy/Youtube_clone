# YouTube Clone Project

This is a YouTube clone project built using Next.js. This project allows you to create a simple version of YouTube where users can browse and watch videos. Before you start using this project, please make sure to follow the instructions below.

## Prerequisites

Before you can run this project, make sure you have the following software installed on your system:

- Node.js: You can download it from [nodejs.org](https://nodejs.org/).
- npm: npm comes bundled with Node.js, so you don't need to install it separately.

## Getting Started

Follow these steps to set up and run the YouTube clone project:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/vijay-vardhan-reddy/youtube-clone.git
   ```

2. Navigate to the project directory:

   ```bash
   cd youtube-clone
   ```

3. Install project dependencies using npm:

   ```bash
   npm install
   ```

4. You need to obtain a YouTube Data API key to fetch video data. Go to the [Google Cloud Console](https://console.cloud.google.com/), create a new project (if you don't have one already), enable the YouTube Data API v3, and create an API key.

5. Open the `index.js` file located in the `pages` directory of the project.

6. Find the following line of code in `index.js`:

   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE';
   ```

7. Replace `'YOUR_API_KEY_HERE'` with the API key you obtained in step 4.

8. Save the `index.js` file.

9. Start the development server:

   ```bash
   npm start
   ```

10. Open your web browser and go to `http://localhost:3000` to access the YouTube clone application.

## Usage

- On the home page, you can browse a list of videos.
- Click on a video to watch it.
- You can also use the search bar to search for specific videos.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. We welcome contributions from the community!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was built with [Next.js](https://nextjs.org/).
- Special thanks to the YouTube Data API for providing access to video data.

Enjoy building your YouTube clone! If you encounter any issues or have questions, feel free to reach out to us.