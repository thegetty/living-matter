This is the repository for *Living Matter: The Preservation of Biological Materials in Contemporary Art*, edited by Rachel Rivenc and Kendra Roth. This digital book was first published May 24, 2022, by the Getty Conservation Institute. It is available online at [https://www.getty.edu/publications/living-matter/](https://www.getty.edu/publications/living-matter/) and may be downloaded free of charge in multiple formats.

## About the Book

Eggshells, flowers, onion peels, sponge cake, dried bread, breast milk—these are just a few of the biological materials that some contemporary artists have used to make art. But how can works made from such perishable ingredients be preserved? And what ethical and conceptual dilemmas might be posed by doing so? Because they are prone to rapid decay, even complete disappearance, biological materials pose a range of unique conservation challenges. This groundbreaking book probes the moral and practical challenges associated with displaying, collecting, and preserving these unique works of art. Theoretical considerations are complemented by a range of specific case studies, thereby affording a comprehensive and richly detailed overview of current thinking and practices on this topic.

With contributions by conservators, scholars, curators, and artists, *Living Matter* is the first publication to address broadly these provocative issues, exploring the role of biological materials in the creative process and presenting a wide variety of possible approaches to their preservation.

## Using this Repository

This is one in series of multiformat publications using [Quire](http://quire.getty.edu)™, Getty’s new publishing framework. Quire is currently in beta, with the goal of it being released as free and open source software in the future. In the meantime, users are encouraged to request access at http://bit.ly/quire-signup. This repository can also be run locally to build the online site (but not the PDF or ebook formats) with [Hugo](https://gohugo.io/), the [static site generator](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/) at the core of Quire.

We are dedicated to maintaining this publication for years to come at the permanent URL, [https://www.getty.edu/publications/living-matter/](https://www.getty.edu/publications/living-matter/), and in its various formats and incarnations. For any updates to the book, we will be following something between an app and traditional book publication model. Updates will only be made in regulated chunks as formal revisions and new editions and will always be thoroughly documented here in the repository, as well as in the revision history included with each of the book’s many formats.

The primary content pieces of the book can be found in the `data` and `content` directories. The master branch represents the current, published edition at all times, and the revisions branch, when present, will show changes currently under consideration. We invite you to submit suggestions or corrections via pull request on the revisions branch, by posting an issue, or by emailing us at [pubsinfo@getty.edu](mailto:pubsinfo@getty.edu).

## Development Notes

This project was last built with the following software versions:

- Quire 0.20.2
- Node 14.18.1 / npm 6.14.15
- Hugo 0.82.1
- PrinceXML 14.2
- Pandoc 2.17.1.1

While version 0.20.2 of the core Quire Default Theme was used, a number of customizations were made:

- Improved search for diacritics
- Copyright statements added to the end of each essay
- Custom cover design to match previous GCI Proceedings volumes

Within the theme itself, changes were made to the `source/css/variables.scss` and `source/css/print.scss` files. Outside of the theme, customizations can be found in the project’s `layouts` directory, and in `static/css/custom.css`.

### Images Submodule

Many of figure images for *Living Matter* are licensed from third parties for use exclusively in this publication. As such, they are kept in a separate, private repository, https://github.com/thegetty/living-matter-images/, which is linked to this main publication repository as a submodule in `static/img/figures/`. When cloning this repo for further development, you’ll permissions for the private repository and will need to clone recursively in order to clone both the main repo and the submodule.

```
git clone --recursive https://github.com/thegetty/living-matter.git
```

## License

© 2022 J. Paul Getty Trust<br />
Text by Marcia Reed, Rachel Rivenc, Kendra Roth, and Timothy P. Whalen © 2022 J. Paul Getty Trust. All other text © the authors.

The text of this work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). All images are reproduced with the permission of the rights holders acknowledged in captions and are expressly excluded from the CC BY-NC license covering the rest of this publication. These images may not be reproduced, copied, transmitted, or manipulated without consent from the owners, who reserve all rights.