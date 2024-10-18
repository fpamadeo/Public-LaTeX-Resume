## Introduction

The public repo for the LaTeX code templates for my one-column resume and cover letters.

## Preview

![Resume Screenshot](/resume_preview.png)

- Screenshot only shows the first page of my resume; a complete copy can be seen in the root of this reporsitory

![Cover Letter Screenshot](/Letter_preview.png)

## Motivation

I've started to incorporate my [brag document](https://jvns.ca/blog/brag-documents/#template) into my resume to make sure I keep track of my professional achievements and overall experience. However, my word document just keeps on getting larger beyond reasonable maintenance, causing it to be harder to format and tailor for each job application.

LaTeX helps with both, with its article DocumentClass and with the ability to comment in and out various parts of my resume, as what is needed with each application.

With the LateX header already in place, I could just use the Letter DocumentClass to make sure my cover letters are consistent with my resumes.

## Design considerations:

- The [TG Pagella](https://www.tug.org/FontCatalogue/texgyrepagella/) font was used for its modern and easy-to-read look.
  - Other candidates were: [Lato](https://ctan.org/pkg/lato), [Carlito](https://ctan.org/pkg/carlito), and [Charter](https://ctan.org/pkg/charter)
- ATS compatibility design choices:
  - Single column format
  - Clickable links, but display text is just the link in plain text.
  -

### Issue/s encountered.

- After following steps outlined in this [VS Code & LaTeX guide](https://mathjiajia.github.io/vscode-and-latex/), I encountered the "Can not find latexindent in PATH." issue.
  - Fix: reran the simple TeX Live installer and restarted VS Code.
