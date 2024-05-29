# Git Practice Repository

## Description
This repository was created for practicing basic Git commands. It contains a simple HTML file that displays an image. The goal is to help developers become familiar with using Git for version control.

## Project Structure
```
.
├── README.md
├── index.html
├── style.css
└── images
    └── example.jpg
```

- `index.html`: Main HTML file that displays the image.
- `images/example.jpg`: Image used in the HTML file.
- `style.css`: Give some style to the HTML file.

## Basic Git Commands

### Add Files to the Index
```bash
git add index.html
git add images/example.jpg
git add style.css
git add readme.md
```

### Make a Commit
```bash
git commit -m "Add index.html and example image"
```

### Check the Status
```bash
git status
```

### Check the Commit History
```bash
git log
```

### Push Changes to the Remote Repository
```bash
git push origin main
```

## How to Use
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/tiemimaeda/aula10_github.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd git-aula10_github
    ```
3. Open the `index.html` file in your browser to view the image.