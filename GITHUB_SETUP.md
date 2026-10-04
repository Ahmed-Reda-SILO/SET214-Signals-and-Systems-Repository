# GitHub setup

## Repository details

| Setting | Value |
| --- | --- |
| Name | `SET214-Signals-and-Systems` |
| Description | SET214 Signals and Systems course materials by Dr. Ahmed Reda Mohamed: MATLAB, signals, LTI systems, convolution, Fourier and Laplace transforms, and sampling. |
| Suggested topics | `signals-and-systems`, `signal-processing`, `matlab`, `electrical-engineering`, `course-materials`, `set214` |

## Upload through GitHub

1. Extract the repository ZIP.
2. Create a GitHub repository named `SET214-Signals-and-Systems` in your intended account and choose the desired visibility.
3. Upload the **contents** of the extracted `SET214-Signals-and-Systems` folder into the new repository. Place `README.md` at the repository root and retain the `lectures/` folder.
4. Commit the upload with the message `Add SET214 Signals and Systems course materials`.
5. Open the repository home page and select a lecture link to confirm the PDF is available.

## Upload using Git

Create an empty GitHub repository first. Replace `YOUR_GITHUB_USERNAME` in the remote URL below with the account or organization that owns it.

Run these commands from the extracted repository folder:

```bash
git init -b main
git add .
git commit -m "Add SET214 Signals and Systems course materials"
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/SET214-Signals-and-Systems.git
git push -u origin main
```

If Git requests an author name or email, configure your own identity before committing. Once uploaded, the README displays the course overview and linked lecture index on the repository home page.
