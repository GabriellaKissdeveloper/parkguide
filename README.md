This project is about showing the national parks around the world with descriptions, pictures, services, possible activities and so on.
The pictures are stored in Cloudinary and the data are stored in MongoDB Atlas.
Visitors can search for parks according to different conditions, such as continent, country, landscape, activity, difficulty or own criteria.
Logged in users can hold feedback and rate the parks (or edit and delete their ratings).
Only admin user can add new parks to the database.


Used software and plugins:
- Node.js, JavaScript, Express, nodemon
- express-session: session middleware, session data is not saved in the cookie itself, just the session ID. Session data is stored server-side.
- Cloudinary: allows to quickly and easily integrate the application with Cloudinary (image storage)
- Multer: a node.js middleware for handling multipart/form-data, which is used for uploading files.
- Multer Storage Cloudinary: multer-storage-cloudinary
- Mapbox SDK: for working with Mapbox APIs, visualizing the national parks in map
- dotenv: loads environment variables from a .env file into process.env
- ejs: embedded JavaScript template
- ejs-mate: Express 4.x layout, partial and block template functions for the EJS template engine.
- mongoose: MongoDB object modeling tool designed to work in an asynchronous environment.
- passport: Express-compatible authentication middleware for Node.js.
- passport-local: Passport strategy for authenticating with a username and password.
- Passport-Local Mongoose: a Mongoose plugin that simplifies building username and password login with Passport.
- sanitize-html: a simple HTML sanitizer, allows you to specify the tags you want to permit, and the permitted attributes for each of those tags
- joi: data validator for JavaScript


Color palette:
navbar background: #e2fadb
text color: #5f634f
other green color: #dbefbc