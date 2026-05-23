[README.md](https://github.com/user-attachments/files/28174063/README.md)
# Garment Dye Lab

Garment Dye Lab is a static front-end prototype for exploring garment dyeing outcomes through procedural texture generation, visual explanation, and output evaluation.

The system presents dyeing as a design workflow: generate dye textures, explain how the visual logic works, and evaluate the results before applying them to garment visuals.

## Main Functions

- Generate procedural dye textures from adjustable parameters.
- Preview color, pattern, density, and texture variations.
- Export generated dye outputs as image-based texture results.
- Explain the relationship between input parameters, drawing logic, layer composition, and final output.
- Compare dye variations through an evaluation interface.
- Present selected dye outputs in a garment application context.

## File Structure

- `Garment_Dyeing_Lab_System_Overview.html`
  - Overview page for the whole system.
  - Introduces the Generate, Explain, and Evaluate workflow.

- `Garment_Dyeing_Lab_V5.html`
  - Main dye texture generator.
  - Contains parameter controls, canvas-based drawing, preview functions, and texture export.

- `Garment_Dyeing_Lab_Portfolio_Explanation.html`
  - Visual logic explanation page.
  - Breaks down the system into steps such as parameter input, pattern generation, layer composition, and export logic.

- `Garment_Dyeing_Lab_Dye_Output_Evaluation_System.html`
  - Dye output evaluation page.
  - Supports comparison of texture variations, evaluation criteria, selected output display, and garment application preview.

## Brief Implementation

The system is built as a collection of static HTML pages with embedded CSS and JavaScript.

Key implementation methods:

1. HTML structures each page and separates the generator, explanation, overview, and evaluation views.
2. CSS defines the visual layout, interface hierarchy, and portfolio-style presentation.
3. JavaScript handles parameter updates, interaction logic, drawing behavior, and export actions.
4. Canvas is used to generate procedural dye textures and image outputs.
5. The dye generator combines multiple visual layers, including base color, dye marks, texture noise, and garment preview elements.
6. Relative links connect the pages into one system without requiring a backend.

## Project Role

This project is a design research and portfolio prototype rather than a production dyeing tool. Its purpose is to demonstrate how digital parameters can shape garment dyeing visuals and how generated outputs can support design selection and evaluation.
