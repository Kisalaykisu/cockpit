# cockpit
A Practical Debugging Tool for Training Deep Neural Networks

<!-- PROJECT LOGO -->
<br />
<p align="center">
<a href="#"><img src="docs/source/_static/Banner.svg" alt="Logo"/></a>
  <h3 align="center">A Practical Debugging Tool for Training Deep Neural Networks</h3>

  <p align="center">
    A better status screen for deep learning.
  </p>
</p>

<p align="center">
  <a href="#installation">Installation</a> •
  <a href="https://cockpit.readthedocs.io/">Docs</a> •
  <a href="#license">License</a> •
  <a href="#citation">Citation</a>
</p>

[![CI](https://github.com/f-dangel/cockpit/actions/workflows/CI.yml/badge.svg)](https://github.com/f-dangel/cockpit/actions/workflows/CI.yml)
[![Lint](https://github.com/f-dangel/cockpit/actions/workflows/Lint.yml/badge.svg)](https://github.com/f-dangel/cockpit/actions/workflows/Lint.yml)
[![Doc](https://img.shields.io/readthedocs/cockpit/latest.svg?logo=read%20the%20docs&logoColor=white&label=Doc)](https://cockpit.readthedocs.io)
[![Coverage](https://coveralls.io/repos/github/f-dangel/cockpit/badge.svg?branch=main&t=piyZHm)](https://coveralls.io/github/f-dangel/cockpit?branch=main)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/f-dangel/cockpit/blob/master/LICENSE)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![arXiv](https://img.shields.io/static/v1?logo=arxiv&logoColor=white&label=Preprint&message=2102.06604&color=B31B1B)](https://arxiv.org/abs/2102.06604)

---

```bash
pip install 'git+https://github.com/f-dangel/cockpit.git'
```

---

**Cockpit is a visual and statistical debugger specifically designed for deep learning.** Training a deep neural network is often a pain! Successfully training such a network usually requires either years of intuition or expensive parameter searches involving lots of trial and error. Traditional debuggers provide only limited help: They can find *syntactical errors* but not *training bugs* such as ill-chosen learning rates. **Cockpit** offers a closer, more meaningful look into the training process with multiple well-chosen *instruments*.

---

![CockpitAnimation](docs/source/_static/showcase.gif)

<!-- Installation -->
## Installation

To install **Cockpit** simply run

```bash
pip install 'git+https://github.com/f-dangel/cockpit.git'
```


