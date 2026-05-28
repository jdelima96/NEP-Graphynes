# NEP potential for hexagonal and rectangular $\gamma$-graphynes

This repository contains the reference datasets and the corresponding trained Neuroevolution Potential (NEP) models developed in the study:

> **Superior directional thermal conductivity and stiffness in rectangular $\gamma$-graphyne revealed by neuroevolution machine-learning potentials**

## 📁 Repository Structure

The data and potential files are organized into two distinct directories based on the material structure:
* `gyg/` - Reference configurations and trained NEP model for pristine/hexagonal $\gamma$-graphyne.
* `rgyg/` - Reference configurations and trained NEP model for rectangular $\gamma$-graphyne.

Each directory contains the respective training (`train.xyz`), testing (`test.xyz`), and trained NEP potential (`nep.txt`) files compatible with the [GPUMD](https://gpumd.org/) package.

> [!CAUTION]
> Note that these datasets and potentials are strictly system-specific and valid only for temperatures up to 1000 K. For the specific parameters and configurations used to generate these files, please refer to the main text of the publication.

## 📄 Citation

If you use these datasets or potentials in your research, please cite our main text:

*J. de Lima, C. F. Woellner. Superior directional thermal conductivity and stiffness in rectangular $\gamma$-graphyne revealed by neuroevolution machine-learning potentials. (2026).*

### BibTeX

```bibtex
@article{deLima2026superior,
  title = {Superior directional thermal conductivity and stiffness in rectangular $\gamma$-graphyne revealed by neuroevolution machine-learning potentials},
  volume = {},
  ISSN = {},
  DOI = {},
  number = {},
  journal = {},
  publisher = {},
  author = {de Lima, Jhionathan and Woellner, Cristiano F.},
  year = {2026},
  month = jul,
  pages = {}
}
``
