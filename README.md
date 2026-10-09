# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is designed for UC Berkeley students, especially newcomers who want to discover useful campus resources for studying, recreation, and student support. Its purpose is to make information about campus facilities and services easier to access. The first eight resources were provided by COMPSS 211A, and I added the Recreational Sports Facility (RSF), using the official UC Berkeley Recreation & Wellbeing website to check its information.

## Website checks

Website: https://aimee68-sketch.github.io/hidden-berkeley/
I updated the existing Morrison Library entry (HB03) by revising its access note and added the Recreational Sports Facility (RSF, HB09) as a new resource. I checked the GitHub CSV and notebook and confirmed that both entries are saved with their intended information. I also opened the official RSF webpage and verified that it provides facility details, membership requirements, and operating-hours information. However, I could not access the published GitHub Pages website to confirm that the displayed values match the CSV. The RSF official link opens the intended page, while the Morrison Library link and its behavior on the published website still need to be checked.
