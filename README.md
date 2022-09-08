# SIGma Presentation Template

Sample output: [PDF](https://github.com/SIGma-UIUC/presentation-format/blob/main/tex-example.pdf).

## Quickstart Using Markdown

I assume you have TeXLive Full and Pandoc installed:
```
sudo apt install texlive-full pandoc
```

Clone this repository.
```
git clone --depth 1 https://github.com/sigma-uiuc/presentation-format
cd presentation-format
```

Export `simple-md-example.md` to PDF by running:
```
pandoc -t beamer simple-md-example.md -o simple-md-example.pdf
```

Open the PDF and make sure it looks as you expect.

Your presentation is ready. To edit a presentation, edit the source
Markdown file, it should be quite intuitive.

In general, you can create another `.md` file and do the exactly
same thing. As long as the `.sty` file and `sigma.png` are in the
same directory, export will work correctly.

# Note
`tex-example` is how you'd use the Beamer theme in pure LaTeX, if
you're so inclined.

