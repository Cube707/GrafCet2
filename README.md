# GrafCet2 Package

With this package sequential function charts can be created following the GRAFCET norm (IEC 60 848). While there are more modern norms for creating
SFC diagrams, I have to create GRAFCETs quiet a lot, so I created this package.
The old [`grafcet` Package](https://ctan.org/pkg/grafcet) doesn't fit more modern approaches and its documentation is completely in French. So I
decided to recreate all needed functionality by stealing the code base of the [`tikz-sfc` package](https://ctan.org/pkg/tikz-sfc) and to include the
additional shapes needed to create complete GRAFCETs. This means that most of its documentation applies for this package as well.

The package is a work in progress. It does work in its current state, but I plan on changing some behaviour as well as adding some more features, if I
can find the time.

## Usage

To use the package, just download the `grafcet2.sty` file and place it next to your project (or in a folder that's on `TEXINPUTS`).

Then you can load the package as you would expect:

```LaTeX
\usepackage{grafcet2}
```

The commands work very similar to the `tikz-sfc` package, so most of its documentation applies. But it's probably easiest if you just look at the example.


### Example

This Example is produced by [`example.tex`](./example.tex):

![example grafcet](./example.png)


# Plans

- [x] allowing for use of `\not{}` in transitions and conditions
- [ ] polishing the tikz-key backend, so that less nesting is needed (no idea how though)
- [ ] adding an easy way to create parallel junctions
- [ ] adding documentation
