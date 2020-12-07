
##  Latex Resume

<div id="badges" lign="center">

  [![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/eclipse-theia/theia)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-curved)](https://github.com/nerosiar/resume/labels/help%20wanted)
  ![License](https://img.shields.io/github/license/nerosiar/resume)
  [![Open questions](https://img.shields.io/badge/Open-questions-blue.svg?style=flat-curved)](https://github.com/nerosiar/resume/labels/question)
  [![Open bugs](https://img.shields.io/badge/Open-bugs-red.svg?style=flat-curved)](https://github.com/nerosiar/resume/labels/bug)

</div>

A single-page, one-column resume for [Nader Rais](https://github.com/nerosiar). It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.

### Motivation

I created this template as managing a resume on Google Docs was hard and changing any formatting was too difficult since it had to be applied in multiple places. Most currently available templates either focus on two columns, or are multiple pages long. I personally found the two-column templates hard to focus while multiple-page resumes were just too long to be used in career fairs.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex nerosiar.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Nerosiar.
