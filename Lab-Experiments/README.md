# Lab Experiments

This folder is for uploading lab experiments for the ITA0324 - Mobile Computing course.

Repository structure and guidelines:

- Create a subfolder for each lab, e.g. `Lab-01`, `Lab-02`, ...
- Inside each lab folder include:
  - a `README.md` describing the experiment, objectives, and steps
  - source code and project files (keep files in their native structure)
  - a `report.md` or `report.pdf` with results and observations
- Use descriptive filenames and include your name/ID when submitting individual student work, e.g. `Alice_12345_Lab-01.zip`.
- If a lab requires an Android/iOS project, include instructions to build and run in the lab's `README.md`.

How to add files:
1. Use the GitHub web UI: click "Add file" → "Upload files" inside the lab folder.
2. Or clone the repo locally, add files, commit, and push:
   ```bash
   git clone https://github.com/Sreenithabhuvanapalli28/ITA0324-Mobile-Computing.git
   cd ITA0324-Mobile-Computing
   mkdir Lab-01
   echo "# Lab 01" > Lab-01/README.md
   git add Lab-01
   git commit -m "Add Lab-01 folder with README"
   git push
   ```

If you'd like, I can create a template subfolder for Lab-01 with example files.