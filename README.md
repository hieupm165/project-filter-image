# **Project Overview:**

The "Udagram Image Filtering Microservice" is a part of the Udacity Cloud Engineering Nanodegree program. It involves creating a web application where users can register, log in, post photos, and process those photos using an image filtering microservice.

## Link github repo: [hieupm165/project-filter-image (github.com)](https://github.com/hieupm165/project-filter-image.git)

## **Tasks:**

1. **Setup Node Environment:**

Initialize a new Node.js project by running `npm i` in the project directory.

Start the development server with `npm run dev`.

2. **Create a New Endpoint in `server.js`:**

In the `server.js` file, create a new endpoint that uses query parameters to download an image from a public URL, apply image filtering, and return the filtered image.

Helper functions for image processing are provided in the `util/util.js` file.

3. **Deploy Your System:**

Follow the deployment process described in the course, including using Elastic Beanstalk (`eb init`, `eb create`, and `eb deploy`) to deploy the image-filtering service.

4. **My Elastic Beanstalk Endpoint:**

http://my-eb-dev-2-env.eba-adfvh3ua.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

5. **Optional: Stand Out Tasks:**

**Elastic Beanstalk Endpoint:** You've provided an Elastic Beanstalk endpoint where your image filtering service can be accessed.
