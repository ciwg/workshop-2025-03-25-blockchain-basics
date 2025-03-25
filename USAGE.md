# Usage

1. Clone this repository
2. Edit the `README.md` file to describe your workshop
3. Edit slides/slides.md to create your slides
4. Run `make` in the slides directory to generate and host the slides

Important:  **Do not edit the `slides.html` file directly**.  It is
automatically generated from `slides.md` by the `make` command.  Any
edits you make to `slides.html` will be lost the next time you run
`make`.

# Optional/later refactorings

Configure the repo on github to turn on github pages for the `slides`
folder (BTD: add/fix instructions for this).

It may make more sense to have the slides.md in the root of the repo
as the README.md instead of having a separate README.md; to do that
we'd need to also move slides.thml, main.go, etc.




