# Frontend Takehome Test

### **Project Description:**

Your task is to create a web application that consumes a collection of images returned by a GraphQL API and allows the user to interact with those photos in some creative way. The end feature set and user experience is totally up to you. This could be as simple as a grid of photos, along with a photo detail view. You may also choose to utilize a generative AI model to allow the user to tweak and create new images. There is no right or wrong end user experience here - we just want to see how you think about product, UX, and the interaction layer of a web app.

### **Requirements:**

1. **Technology Stack:**
    - Preferably, use React/NextJS for the frontend (could be a simple create-next-app), but you may use an alternative like Svelte if you’re more comfortable with that.
    - Implement Apollo Client to fetch data from a mocked GraphQL API that we will provide. This API will return a list of images and some metadata.
    - Consider integrating an AI model (e.g., a deep learning model) to incorporate a generative image feature.
2. **How to use the Mock API:**
    - Included is a mock GraphQL API. To run locally, follow these steps:
        1. Create a new repo with the included `package.json` and `server.js` files. Make sure to include the `posts.json` in the repo as well. This is the mocked dataset that includes 20 images and some meta data.
        2. From the root of the new repo, install dependencies: `npm install`
        3. Start graphQL server: `npm start`
        4. Visit the graphQL playground in the browser to test API: [`http://localhost:4000/`](http://localhost:4000/)
3. **AI Image Enhancement (Optional):**
    - If you decide to implement an AI related feature, consider using pre-trained models or APIs for image processing.
4. **Design and Interaction:**
    - Prioritize user experience and design to create an engaging and intuitive interface.
    - Implement smooth transitions and interactions, such as animations when viewing posts or enhancing images.
    - Ensure responsive design for various screen sizes.
5. **Code Quality:**
    - Write clean, maintainable, and well-documented code.
    - Properly structure your components and project folders.
    - Use state management (e.g., Redux, Apollo Client) if necessary.
    - Ensure error handling and display user-friendly error messages when needed.
6. **Testing:**
    - Testing should be a lower priority, and only do if you have time left over.
    - If so, write unit tests for critical components or functions (e.g., using Jest and React Testing Library).
7. **Deployment:**
    - Only deploy if you have time. It’s also acceptable to hand off the repo, and do a demo locally.
    - If you chose to deploy the application, use a hosting platform of your choice (e.g., Vercel, Netlify).

**Submission:**

- Share your project's code repository.
- Provide clear instructions on how to run the project locally.
- Include any additional documentation or notes you think are relevant.

**Evaluation Criteria:**

- You will be assessed mainly in 2 categories:
    1. Architecture - setting up the building blocks of the application, and managing/caching data throughout the app.
    2. Interaction/UX/Feature set - How have you decided to display the data to the user? What does it look like and feel like to click around the interface?
- Additional evaluation criteria include:
    - Code quality and organization.
    - User interface design and interaction.
    - Responsiveness and cross-browser compatibility.
    - Integration of the mocked GraphQL API
    - Error handling and edge cases.
    - Testing and test coverage (if applicable).
    - Deployment and presentation of the project.

**Note:** The estimated time for this project is 4-8 hours. Please don’t spend more time on it than that, unless you feel so called!