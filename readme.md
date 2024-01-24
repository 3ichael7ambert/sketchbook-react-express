**Use Case and Description for Sketchbook React Application:**
**[Sketchbook Live APP](http://sketchbook-react.surge.sh)**
**1. Live React Application:**
   - **URL:** [Sketchbook React](http://sketchbook-react.surge.sh)
   - **Description:** The live React application serves as the front end for the Sketchbook project. Users can access the application through the provided URL. It provides an interactive drawing canvas where users can create and save drawings.

**2. Loading Drawings:**
   - **URL Format:** [Load Drawing](http://sketchbook-react.surge.sh?canvasId={id})
   - **Description:** Users can load specific drawings by appending the canvas ID to the URL. This feature allows users to revisit or share their saved drawings with others easily.
    - http://sketchbook-react.surge.sh?canvasId={id}
  
  
**3. Express Backend API:**
   - **Base URL:** [Sketchbook Express Backend](https://sketchbook-express-backend.onrender.com/)
   - **Description:** The Express backend serves as the API for the Sketchbook React application, handling various functionalities related to canvas management and drawings.

**4. API Endpoints:**
   - **Get Drawing by ID:**
      - **Endpoint:** `https://sketchbook-express-backend.onrender.com/canvas/:id`
      - **Description:** Retrieve a specific drawing by providing its ID. This allows the React application to fetch and display saved drawings.

   - **Get All Drawings:**
      - **Endpoint:** `https://sketchbook-express-backend.onrender.com/canvas`
      - **Description:** Retrieve a list of all drawings. Useful for displaying a gallery or managing user drawings within the application.

   - **Get Random Drawing:**
      - **Endpoint:** `https://sketchbook-express-backend.onrender.com/random`
      - **Description:** Fetch a random drawing from the database. This can be used to showcase diverse user-generated content or provide inspiration.

**5. Submodules:**
   - **Frontend Repository:**
      - **URL:** [Sketchbook React Frontend](https://github.com/3ichael7ambert/sketchbook-react-frontend/tree/c826d414fcbd3c90e290e34b222978a995f04aeb)
      - **Description:** The frontend repository contains the React application code. Developers can explore and contribute to the frontend to enhance user interface and experience.

   - **Express Backend Repository:**
      - **URL:** [Sketchbook Express Backend](https://github.com/3ichael7ambert/sketchbook-express-backend/tree/ae692228b49ab90cea685562a356f8089ffae8eb)
      - **Description:** The backend repository contains the Express server code responsible for handling API requests. Developers can contribute to backend features, database interactions, and overall server functionality.

**Note:** Ensure that appropriate authentication and authorization mechanisms are in place to protect user data and drawings. Additionally, the provided URLs and endpoints should be used responsibly and in accordance with the project's terms of service.
