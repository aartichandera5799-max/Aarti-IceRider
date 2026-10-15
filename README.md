# IceRider Logistics

IceRider is a class-project cold-chain logistics website. Sample shipment numbers, routes, readings, and estimates are illustrative and are not live company data.

## Files

- `index.html` — website structure and content
- `styles.css` — page design and responsive layout
- `app.js` — navigation, sample tracking, freight estimate, daily brief, RaahNama analysis, and demo assistant
- `images/` — IceRider share-card image and brand emblem
- `server.py` and `render.yaml` — optional Render deployment configuration

The assistant and incident analysis use local demo behavior when no AI backend is configured. GitHub Pages cannot run the Python server, so this static version remains a demonstration; it does not provide live tracking or model-powered AI.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository for the project.
2. Extract this ZIP and upload the files and `images` folder from inside it to the repository's top level. Do not upload the ZIP itself.
3. Commit the upload to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait for the Pages deployment to finish. GitHub will show the public website link in the Pages settings.

## Optional: publish with Render

The included `render.yaml` defines one web service named `icerider`. In Render, create a Blueprint from this repository and select the `render.yaml` file. After deployment, copy the service URL shown in the Render Dashboard. The generated address may vary if the name is unavailable.
