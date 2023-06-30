# CV Template

This repository offers a streamlined, easy-to-customize CV template created with LaTeX. It provides the following key sections:

- Headline
- Address
- About Me
- Work Experience
- Educational Background
- Honors & Awards
- Courses & Certifications
- Technical Skills & Expertise

## Getting Started

Follow these instructions to install and utilize this CV template.

### Step 1: Set Up LaTeX Environment

Firstly, you need to have LaTeX installed in your system. To do this, you can follow the guide on the official [LaTeX Project](https://www.latex-project.org/get/) website.

For Ubuntu users, [TeXstudio](https://www.texstudio.org/), a comprehensive LaTeX writing environment, can be installed using the following command in the terminal:

```
sudo apt install texstudio
```

This will install both the LaTeX environment and editor.

### Step 2: Customization and Compilation

To personalize your CV, open the `cv.tex` file in your preferred editor and modify each section according to your personal information and professional experience.

After you have customized your CV, compile it into a `.pdf` file by doing the following:

Navigate to the project directory by typing the following command in your terminal:

```
cd /path/to/cv
```

Next, compile the LaTeX file using `pdflatex`:

```
pdflatex cv.tex
```

You should now have a PDF version of your customized CV in your project directory.

**Note:** Ensure the `.cls` file is located in your working directory before compiling, as it's essential for the proper compilation of the `cv.tex` file.

## Issues

For any problem encountered during the installation or compilation process, please open an issue on this repository.