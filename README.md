# tutorials

Minimal template repository for Jupyter notebooks used to learn core ideas with visual explanations.

## Goal
Each notebook should focus on one concept and use the [Manim Community](https://www.manim.community/) project to build visual intuition across topics such as math, chemistry, biology, and physics.

## Quick start
1. Install/sync dependencies:
   ```bash
   uv sync
   ```
2. Launch JupyterLab:
   ```bash
   uv run jupyter lab
   ```
3. Open `notebooks/00_template.ipynb` and duplicate it for a new lesson.

## Repository structure
- `notebooks/00_template.ipynb`: starter notebook template with a Manim scene scaffold
- `pyproject.toml`: minimal dependency and project metadata for `uv`

## Notes
- This repository is intentionally minimal and designed for local learning workflows.
- It is not packaged for PyPI distribution.
