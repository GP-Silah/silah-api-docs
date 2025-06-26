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
- The source `swagger.json` is generated from the [Silah Backend](https://github.com/GP-Silah/silah-backend) repository and updated here for consistency.

---

## Updating the Docs

1. Regenerate the latest `swagger.json` from the [Silah Backend](https://github.com/GP-Silah/silah-backend).
2. Replace the existing `swagger.json` file in the `docs/` folder.
3. Commit and push changes to this repository.
4. Redeploy on GitHub Pages to update the hosted documentation.

---

## Contact

For any issues or contributions, please reach out to the Silah Backend Team.
