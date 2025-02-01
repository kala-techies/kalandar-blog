# Kalandar's Personal Blog

This is a personal blog website built with React.js. It showcases my passion for technology and contains various sections like About Me, Blog Posts, and Contact Information.

## Project Structure

The project is structured as follows:

- **public/**: Contains static assets.
- **src/**: Contains all the React components, styles, and pages.
- **Dockerfile**: Used for building a Docker image.
- **webpack.config.js**: Webpack configuration for bundling.

## Running the Project Locally


## Prerequisites

- **Node.js**: Version 14.x or above
- **Docker**: Installed and running

## Getting Started

### 1. Clone the repository
git clone https://github.com/2193306](https://github.com/kala-techies/kalandar-blog.git

cd kalandar-blog


1. Install dependencies:
   npm install
2. npm start
## The application will be accessible at http://localhost:3000.

## Building the Docker Image
   1.  docker build -t kalandar-blog .
   2.   docker run -p 3000:3000 kalandar-blog
## The application will be accessible at http://localhost:3000 (or the appropriate IP address if you are accessing it from another device).

## happy learinig
## cheers!!

## Helpful commands:
1. docker tag kalandar-blog kala81/blog:latest
2. Log in to Docker Hub:

docker login
Push the image:
docker push kala851/blog:latest
