# durhamuni-poster

A LaTeX poster style inspired by the style from University of Calgary which I adapted for Advanced Research Computing of Durham University (ARC DU), to use with the
[tikzposter](https://ctan.org/pkg/tikzposter?lang=en) document class.

`durhamuni-poster.sty` contains all the code required, and provides a
`DurhamUni` theme for `tikzposter` (which is loaded automatically). 

It also provides a `\footer` command which lets you add a footer at
the bottom of the poster (for sponsor logos, etc.), and a
`\tpsetpostersize` command that adjusts the internal dimensions after
you've changed the poster size with `\geometry`, if the poster sizes
provided by `tikzposter` are not suitable.

`issotl-poster.tex` is an example. The ARC DU logo in
the header is provided as `OfficialARC448px.png`. You'll need
to get your sponsor logos from somewhere else. Try to get a PNG, a PDF, or EPS
and convert to PDF (e.g., run through
[`epstopdf`](https://ctan.org/pkg/epstopdf?lang=en)). Or you can try to request
department lockups and wordmarks from your university.
