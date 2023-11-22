# Frontend Takehome Test

### **Project Description:**

Your task is to create a web application that consumes a collection of images returned by a GraphQL API and allows the user to interact with them in some creative way. As a starting point, please reference the Cosmos in-app photo grid (if you still don't have invite code, please ask for one). The idea here is to take inspiration from the design language and general aesthetic of Cosmos, but to come up with a fresh and interesting way of interacting with and displaying the images returned by the API.

In addition, we'd love to see your product thinking, as this is a very product focussed-role. As a final part of this assessment, please include a simple project proposal doc that introduces a new experience on Cosmos. This could be anything from a new way of interacting with elements, to an entirely new feature. We encourage you to think as big as possible here, without the constraints of needing actual bandwidth to complete it. This proposal should include a summary of the feature set, a list of technical requirements, any unknowns and open questions, and an estimate of work.

---

### **Requirements:**

1. **Technology Stack:**
   - Preferably, use React/NextJS for the frontend (could be a simple create-next-app), but you may use an alternative like Svelte if you’re more comfortable with that.
   - Implement Apollo Client to fetch data from a mocked GraphQL API that we will provide. This API will return a list of images and some metadata.
   - Utilize a CSS or CSS in JS library / framework for styling.
   - Preferably, use TypeScript with well defined types.
2. **How to use the Mock API:**
   - Included is a mock GraphQL API. To run locally, follow these steps:
     1. Create a new repo with the included `package.json` and `server.js` files. Make sure to include the `posts.json` file in the repo as well. This is the mocked dataset that includes 20 images and some meta data.
     2. From the root of the new repo, install dependencies: `npm install`
     3. Start graphQL server: `npm start`
     4. Visit the graphQL playground in the browser to test API: `[http://localhost:4000/](http://localhost:4000/)`
     5. You may wish to rename the npm script as you incorporate a frontend, but up to you whether you want to include this in the same repo or not.
3. **Design and Interaction:**
   - Prioritize user experience and design to create an engaging and intuitive interface.
   - Implement smooth transitions and interactions, such as animations when loading and viewing images.
   - Ensure responsive design for various screen sizes.
4. **Code Quality:**
   - Write clean, maintainable, and well-documented code.
   - Properly structure your components and project folders.
   - Use state management (e.g., Redux, Apollo Client) if necessary.
   - Ensure error handling and display user-friendly error messages when needed.
5. **Testing:**
   - Testing should be a lower priority, and only do if you have time left over.
   - If so, write unit tests for critical components or functions (e.g., using Jest and React Testing Library).
6. **Deployment:**
   - Only deploy if you have time. It’s also acceptable to hand off the repo, and do a demo locally.
   - If you chose to deploy the application, use a hosting platform of your choice (e.g., Vercel, Netlify).

**Submission:**

- Share your project's code repository.
- Provide clear instructions on how to run the project locally.
- Include any additional documentation or notes you think are relevant.
- We will setup a demo and code walkthrough on completion.
- Share the project proposal as text document in the repo.

**Evaluation Criteria:**

- You will be assessed mainly in 2 categories:
  1.  Architecture - setting up the building blocks of the application, and managing/caching data throughout the app.
  2.  Interaction/UX/Feature set - How have you decided to display the data to the user? What does it look like and feel like to click around the interface?
  3.  Product thinking - your project proposal demonstrates your ability to think about features and scope of work, and gets us excited about the way you think about what Cosmos could be!
- Additional evaluation criteria include:
  - Code quality and organization.
  - User interface design and interaction.
  - Responsiveness and cross-browser compatibility.
  - Integration of the mocked GraphQL API
  - Error handling and edge cases.
  - Testing and test coverage (if applicable).
  - Deployment and presentation of the project.

**Note:** The estimated time for this project is around 5-6 hours.
