# Lume - AI-powered Architectural Visualization

AI-powered Architectural Visualization SaaS built with React, TypeScript, and Puter, transforming 2D floor plans into photorealistic 3D renders with permanent hosting and persistent metadata.

Live Demo: https://lume-47f7.vercel.app/

## Tech Stack ⚡

- React – Component-based SPA architecture for modern, responsive UI.

- TypeScript – Adds static typing to JavaScript for safer, maintainable code.

- Vite – Blazing fast frontend tooling and optimized build system.

- TailwindCSS – Utility-first CSS framework for rapid and consistent UI design.

- Puter – Cloud platform providing serverless Workers, permanent file hosting, KV storage, and AI model hosting.

- Puter.js – Official SDK for frontend integration with Puter services.

- Claude & Gemini – State-of-the-art AI models powering 2D-to-3D architectural transformations.

- CodeRabbit – AI-powered code review platform used for code quality insights and security.

## Features 🌟

- 2D-to-3D Visualization – Transform flat floor plans into photorealistic 3D models instantly.

- Persistent Media Hosting – Every upload and render gets a permanent public URL.

- Dynamic Project Gallery – Track and manage your visualization history with metadata persistence.

- Side-by-Side Comparison – Compare original floor plans with AI-rendered 3D outputs interactively.

- Privacy Controls – Public and private toggles to control visibility of projects.

- Ownership Mapping – Metadata system tracking project details and user IDs.

- Modern Export Functionality – Download AI-generated renders for presentations or workflows.

- Sharing Options – Easily share your architectural visualizations with others.

…and more, including modular code architecture, reusability, and scalable design.

## How It Works 🛠️

1. Upload a 2D floor plan image.

2. The AI model (Claude or Gemini) generates a 3D photorealistic render.

3. The rendered output is stored permanently with metadata in Puter KV storage.

4. Users can view, compare, export, and share renders easily through the Lume interface.

## Cloning the Repository 🛠️

Clone the Lume repository and navigate into it:
```bash
git clone https://github.com/ayushdwivedi001/Lume.git
cd Lume
```
Install the project dependencies using npm:
```bash
npm install
```
### Set Up Environment Variables 🔑
Create a new file named .env.local in the root of your project and add the following content:
```bash
VITE_PUTER_WORKER_URL="https://your-worker-name.puter.work"
```
Replace the placeholder with your actual Puter worker URL.
You can create one by signing up at Puter.com and publishing your worker.

## Running the Project 🚀

Start the development server:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run dev
```
Open your browser and go to:
```bash
http://localhost:5173
```
You should now see Lume running locally with full functionality.

## 🔮 Future Improvements

- Real-time collaborative architectural editing
- Advanced material and lighting controls
- Multi-angle 3D walkthrough exports
- User profiles with saved design presets
- Community-driven inspiration and remix system
- Improved AI model selection and fine-tuning

