# resume
![CI](https://github.com/sergicanet9/resume/actions/workflows/ci.yml/badge.svg)

My digital resume written in Markdown and autogenerated in different formats:
- [HTML](https://htmlpreview.github.io/?https://github.com/sergicanet9/resume/blob/main/index.html)
- [PDF](https://raw.githubusercontent.com/sergicanet9/resume/main/resume-sergi-canet.pdf)

## Source file
- [src/resume.md](https://github.com/sergicanet9/resume/blob/main/src/resume.md)

## Generate output
After pushing to `main` branch, the CI Github Action generates and commits the HTML and PDF output files.

## Publish ouput
After pushing a new `tag`, the CD Github Action publishes the output at:
- [sergicanet.com](https://www.sergicanet.com)