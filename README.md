# Ultimate Gates of Hell 

<div align="center">
  <img src="static/images/come-on.webp" alt="Bayonetta" width="200">
</div>

The definitive, open-source Bayonetta guide for Super Smash Bros. Ultimate. Hosted on GitHub Pages and built for quick access to every resource. You can access it [here](https://aoex2612.github.io/Ultimate-Gates-of-Hell/).

## What's Inside?

This project is a comprehensive knowledge base covering every aspect of playing Bayonetta at a competitive level:

*   **Framedata:** Detailed breakdowns of every move and how they work.
*   **Combo Guides:** From bread-and-butter routes to mechanically complex executions.
*   **Matchup Guides:** Deep dives into neutral, advantage, and disadvantage states for specific characters, plus a couple of VODs from different top Bayonetta reps.
*   **Advanced Tech & Movement:** Stage-specific movement, dabk applications, stalling, footstool confirms, witch strikes, and more.

## Roadmap

### Completed!
*  **Initial Matchup Guides:** Fully detailed strategies for a couple matchups I needed to prepare for, including VODs and specific neutral/advantage/disadvantage breakdowns.

### In Progress. . .
*  **Roster Expansion:** Building out the grid and individual pages for the rest of the cast (and there's quite a lot!).
*   **Combo Foundations:** Drafting the initial text structure for the bread-and-butter combo section.

### To-Do
*   **Framedata Population:** Add specific hitbox properties, active frames, and safety on shield for all moves. (Will probably copy-paste UFD's data for these).
*   **Stage Strategies:** Write the movement and tech guides for all legal competitive stages.
*   **SEO Optimization:** Configure metadata, tags, and open-graph descriptions for better search engine indexing.

## Stack & Local Development
This site is purely static, fast, and entirely Markdown-driven.

*   **Framework:** [Hugo](https://gohugo.io/)
*   **Theme:** [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
*   **Hosting:** GitHub Pages 

To run the project locally on your machine:

```bash
# Clone the repository including the Hugo theme submodule
git clone --recurse-submodules git@github.com:Aoex2612/Ultimate-Gates-of-Hell.git

# Navigate into the directory
cd Ultimate-Gates-of-Hell

# Spin up the local Hugo development server
hugo server -D

```
Visit `http://localhost:1313/` in your browser.
