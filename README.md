# EauSure-Sysml

This repository contains SysML diagrams written in PlantUML for the EauSure system.

**Files**
1. `*.plantuml` are the source diagrams
2. `*.svg` are the rendered outputs

## Clone the repository
```bash
git clone <repo-url>
cd Sysml
```

## Preview PlantUML diagrams
### Option 1: PlantUML website
1. Open any `.plantuml` file and copy its content.
2. Go to https://www.plantuml.com/plantuml/uml/
3. Paste the content to render the diagram and export/download as SVG if needed.

### Option 2: VS Code extension + Live Server
1. Install the **PlantUML** extension (by jebbs) in VS Code.
2. Open a `.plantuml` file and use **Command Palette** -> `PlantUML: Preview Current Diagram` for an in-editor preview.
3. Use `PlantUML: Export Current Diagram` to generate or refresh the `.svg`.
4. Install **Live Server**, then right-click the `.svg` and choose **Open with Live Server**; re-export after edits to refresh the browser view.

## Test locally
There are no automated tests. To validate locally, render the `.plantuml` files to SVG (via the website or the VS Code extension) and open the resulting `.svg` files to confirm they display correctly.
