# Silah API Documentation

This repository hosts the **static Swagger UI files** for the Silah backend API documentation.  
It serves the interactive API docs so that the frontend team and other developers can conveniently explore and understand the API endpoints.

---

## Hosted Link

The API documentation is accessible at:

[https://docs.silah.site](https://docs.silah.site)

---

## How it works

- The `docs/` folder contains all the static files including the generated `swagger.json`.
- These files are served as a static website, enabling the Swagger UI interface to load and display API docs.
- The source `swagger.json` is automatically generated from the [Silah Backend](https://github.com/GP-Silah/silah-backend) repository and updated here using a GitHub Actions workflow.  
- Updates are pushed automatically to this repository whenever changes are made to the backend API.

---

## Updating the Docs

Thanks to the automated workflow, manual updates are no longer required. The workflow:

1. Listens for changes pushed to the `main` branch of the Silah Backend repository.
2. Builds the backend and generates the latest `swagger.json`.
3. Pushes the updated `swagger.json` to this repository automatically.
4. Deploys the updated documentation on GitHub Pages.

> We do **not** need to manually regenerate or push the docs anymore. The process is fully automated.
