# BlogPost Website

This repository contains the code for a simple blog website that allows users to create new posts. The website was built using HTML, CSS, Node.js, Express, and MongoDB.

## Installation

To run this project on your local machine, you need to follow these steps:

1. Clone the repository by running the following command in your terminal: 

    `git clone https://blogpost-website-production.up.railway.app/`

2. Change the directory to the project directory using the following command:

    `cd blogpost-website`

3. Install the dependencies by running the following command:

    `npm install`

4. Create a `.env` file in the root directory of the project and set the environment variables according to your own configuration. The following variables are required:

    ```
    MONGODB_URI=<your-mongodb-uri>
    PORT=<your-server-port>
    ```

5. Start the server by running the following command:

    `npm start`

6. Open your web browser and navigate to `http://localhost:<your-server-port>` to view the website.

## Usage

The website allows users to view existing blog posts, as well as create new ones. To create a new post, click on the "New Post" button in the navigation bar, and fill out the form with the post title and content. Click on the "Submit" button to save the post.

## Contributing

Contributions to this project are always welcome. If you find a bug or have a feature request, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
