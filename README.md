# GrafCet2 Package

With this package sequential function charts can be created following the GrapCet norm (IEC 60 848). While there are more modern norms for creating
SFC diagramms, I have to create GrafCets quiet a lot, so I created this package.  
The old [`grafcet` Package](https://ctan.org/pkg/grafcet) doesn't fit more modern approaches and its documentation is completely in france. So I
decided to recreate all needed functionality by stealing the code base of the [`tikz-sfc` package](https://ctan.org/pkg/tikz-sfc) and to include the
additional shapes needed to create complete GrafCets. This means that most of it's documentation applies for this package as well.  

The package is a work in progress. It does work in its current state, but I plan on changing some behaviour as well a adding some more features, if I
can find the time.

# Plans:
- allowing for use of `\not{}` in transitions and conditions
- polishing the tikz-key backend, so that less nesting is needed (no idea how though)
- adding an easy way to create parallel junctions
- adding documentation