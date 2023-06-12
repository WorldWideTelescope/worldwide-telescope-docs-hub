[![Build Status](https://dev.azure.com/aasworldwidetelescope/WWT/_apis/build/status/WorldWideTelescope.worldwide-telescope-docs-hub?branchName=master)](https://dev.azure.com/aasworldwidetelescope/WWT/_build/latest?definitionId=9&branchName=master)
[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

# WWT Docs Hub website: Source Code

This repository contains the source code for the hub page of

### https://docs.worldwidetelescope.org/

If you’re just interested in the documentation itself, you should go to that
website. If you’re interested in *contributing* to that website, you’ve come
to the right place!

[//]: # (numfocus-fiscal-sponsor-attribution)

The WorldWide Telescope project uses an [open governance
model](https://worldwidetelescope.org/about/governance/) and is fiscally
sponsored by [NumFOCUS](https://numfocus.org/). Consider making a
[tax-deductible donation](https://numfocus.org/donate-for-worldwide-telescope)
to help the project pay for developer time, professional services, travel,
workshops, and a variety of other needs.

<div align="center">
  <a href="https://numfocus.org/donate-for-worldwide-telescope">
    <img height="60px"
         src="https://raw.githubusercontent.com/numfocus/templates/master/images/numfocus-logo.png">
  </a>
</div>


## Quick Start for the Initiated

The manual is a static site written in [CommonMark Markdown] and processed
with [Zola]. Zola is distributed as a single executable so it is ridiculously
[easy to install][install-zola]. Once you have Zola all you have to do is run

```
zola serve
```

to build the site and serve it locally for testing. The command `zola check`
will check the build and verify that outgoing links are valid. Zola has
[lots of documentation][zola-docs].

[CommonMark Markdown]: https://commonmark.org/
[Zola]: https://getzola.org/
[install-zola]: https://www.getzola.org/documentation/getting-started/installation/
[zola-docs]: https://www.getzola.org/documentation/getting-started/overview/

Merges to `master` will be published automatically using WWT’s continuous
deployment infrastructure.


## Contributing

Contributions are welcome! If you’re new to the project, please see the
[WWT Contributors’ Guide] and the [WWT Code of Conduct]. We operate with a
standard [fork-and-pull] model.

[WWT Contributors’ Guide]: https://worldwidetelescope.github.io/contributing/
[WWT Code of Conduct]: https://worldwidetelescope.github.io/code-of-conduct/
[fork-and-pull]: https://help.github.com/en/articles/about-collaborative-development-models


## Acknowledgments

Work on the WorldWide Telescope system has been supported by the [American
Astronomical Society] (AAS), the [.NET Foundation], and other partners. See [the
WWT user website][acks] for details.

[American Astronomical Society]: https://aas.org/
[.NET Foundation]: https://dotnetfoundation.org/
[acks]: https://worldwidetelescope.org/about/acknowledgments/

