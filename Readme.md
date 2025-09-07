# 🍃 The Leaf Network - Multi-AI Smart Farming Platform

This is a single-file React application designed for easy deployment on static site hosting services like Vercel.

### File Structure

The entire application is contained within a single `index.html` file, which includes all the HTML structure, CSS styling, and JavaScript logic. This makes it a self-contained unit that can be deployed without any complex build steps.

### Getting Started

1.  **Save the file:** Ensure your code is saved as a single file named `index.html`.

2.  **Add Your API Keys:** Open the `index.html` file and find the `API_CONFIG` object in the JavaScript section. You must replace the placeholder values with your actual API keys.

    ```javascript
    const API_CONFIG = {
        GEMINI_API_KEY: "YOUR_GEMINI_API_KEY",
        OPENWEATHER_API_KEY: "YOUR_OPENWEATHER_API_KEY",
        AGRO_API_KEY: "YOUR_AGRO_API_KEY",
        // ...
    };
    ```

3.  **Local Development (Optional):** You can open `index.html` directly in your web browser to test the application locally before deployment.

### Deployment on Vercel

Vercel is an excellent platform for deploying static sites like this one. To deploy your project:

1.  **Create a Git Repository:** Initialize a new Git repository on a platform like GitHub or GitLab.

2.  **Add `index.html`:** Add your `index.html` file to the repository.

3.  **Commit and Push:** Commit your changes and push the code to your remote repository.

4.  **Connect to Vercel:** Go to Vercel, create a new project, and import your repository.

Vercel will automatically detect the static file and deploy your application. You'll be provided with a live public URL to access your smart farming dashboard.
