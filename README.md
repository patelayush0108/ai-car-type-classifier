# AI Car Type Classifier

A static website for Practical 15. It uses Transformers.js and a pretrained CLIP model to compare an uploaded image against vehicle-category text prompts. Inference is performed in the browser; no API token or Python backend is needed.

## Deploy with GitHub Pages
1. Sign in at https://github.com/ and create a new repository named `ai-car-type-classifier`.
2. Upload `index.html` and `README.md` to the repository root and commit the files.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait a few minutes, refresh the Pages section, and open the published URL displayed there.

## Notes
- The first use downloads JavaScript/model files, so allow time and keep the tab open.
- A modern browser and internet connection are required.
- Predictions are estimates and may be inaccurate; this is a demonstration, not a safety-critical system.
- If model downloads fail on the hosted site, test the browser console and try again or use Google Colab.

## Practical record
**Aim:** To create and deploy a simple AI-based car type classifier using a cloud-based website.

**Technology:** HTML, CSS, JavaScript, Transformers.js and a pretrained CLIP model.

**Categories:** SUV, hatchback, sedan, sports car, pickup truck, van/minivan.

**Result:** Created a browser interface to upload a car image and display AI-predicted vehicle categories with scores.
