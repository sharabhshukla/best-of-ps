<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Open Source Libraries for Power System Analysis
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome projects for power system analysis. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-15-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/jinningwang/best-of-ps/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/jinningwang/best-of-ps?color=green&label=updated"></a>
</p>

This curated list contains 15 awesome open-source projects with a total of 3.2K stars grouped into 9 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/jinningwang/best-of-ps/issues/new/choose), submit a [pull request](https://github.com/jinningwang/best-of-ps/pulls), or directly edit the [projects.yaml](https://github.com/jinningwang/best-of-ps/edit/main/projects.yaml). Contributions are very welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Dynamic](#dynamic) _1 projects_
- [Steady State](#steady-state) _6 projects_
- [Optimizer](#optimizer) _1 projects_
- [Machine/Reinforcement Learning](#machinereinforcement-learning) _1 projects_
- [Power System Data](#power-system-data) _2 projects_
- [Co-Simulation](#co-simulation) _2 projects_
- [Gas](#gas) _1 projects_
- [Visualization](#visualization) _1 projects_
- [Messaging](#messaging) _0 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://github.com/CURENT/ltb2/blob/main/images/icon/LTB.ico" style="display:inline;" width="13" height="13">&nbsp; CURENT Large-scale Testbed projects
- <img src="https://github.com/CURENT/ltb2/blob/main/images/icon/CURENT_Logo_Transparent.ico" style="display:inline;" width="13" height="13">&nbsp; CURENT, Center for Ultra-Wide-Area Resilient Electric Energy Transmission Networks
- <img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Power system analysis projects written in Python
- <img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13">&nbsp; Power system analysis projects written in Python
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project

<br>

## Dynamic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Power System Dynamic Simulation._

<details><summary><b><a href="https://www.nrel.gov/analysis/siip.html">PowerSimulationsDynamics</a></b> (🥈17 ·  ⭐ 100) - Dynamic Power System simulations; Part of the SIIP at.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-SIIP/PowerSimulationsDynamics.jl) (👨‍💻 10 · 🔀 24 · 📋 110 - 31% open · ⏱️ 29.11.2022):

	```
	git clone https://github.com/NREL-SIIP/PowerSimulationsDynamics.jl
	```
</details>
<br>

## Steady State

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Power System Steady State Simulation_

<details><summary><b><a href="https://www.pandapower.org/">pandapower</a></b> (🥇31 ·  ⭐ 570) - Convenient Power System Modelling and Analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/e2nIEE/pandapower) (👨‍💻 95 · 🔀 370 · 📦 180 · 📋 770 - 18% open · ⏱️ 30.11.2022):

	```
	git clone https://github.com/e2nIEE/pandapower
	```
- [PyPi](https://pypi.org/project/pandapower) (📥 11K / month):
	```
	pip install pandapower
	```
- [Conda](https://anaconda.org/anaconda/pandapower):
	```
	conda install -c anaconda pandapower
	```
- [Docker Hub](https://hub.docker.com/r/pauldepraz/pandapowerapi) (📥 85 · ⏱️ 09.02.2021):
	```
	docker pull pauldepraz/pandapowerapi
	```
</details>
<details><summary><b><a href="https://www.advancedgridinsights.com/gridcal">GridCal</a></b> (🥈20 ·  ⭐ 300) - Cross-platform power systems software. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/SanPen/GridCal) (👨‍💻 27 · 🔀 71 · 📥 23 · 📦 2 · ⏱️ 13.10.2022):

	```
	git clone https://github.com/SanPen/GridCal
	```
- [PyPi](https://pypi.org/project/GridCal) (📥 710 / month):
	```
	pip install GridCal
	```
</details>
<details><summary><b><a href="https://matpower.org/">matpower</a></b> (🥈20 ·  ⭐ 280) - Steady state power flow simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/MATPOWER/matpower) (👨‍💻 12 · 🔀 120 · 📥 140K · 📋 120 - 8% open · ⏱️ 23.11.2022):

	```
	git clone https://github.com/MATPOWER/matpower
	```
- [PyPi](https://pypi.org/project/matpower) (📥 93 / month):
	```
	pip install matpower
	```
- [Docker Hub](https://hub.docker.com/r/matpower/matpower) (📥 340 · ⏱️ 23.11.2022):
	```
	docker pull matpower/matpower
	```
</details>
<details><summary><b><a href="https://www.nrel.gov/analysis/siip.html">PowerSimulations</a></b> (🥈20 ·  ⭐ 180 · ➕) - Optimization Simulation and Modeling of Power.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-SIIP/PowerSimulations.jl) (👨‍💻 28 · 🔀 42 · 📋 220 - 7% open · ⏱️ 09.11.2022):

	```
	git clone https://github.com/nrel-siip/powersimulations.jl
	```
</details>
<details><summary><b><a href="rwl.github.io/PYPOWER/api/">PYPOWER</a></b> (🥉19 ·  ⭐ 250) - Port of MATPOWER to Python. <code><a href="https://tldrlegal.com/search?q=BSD">❗️BSD</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwl/PYPOWER) (👨‍💻 18 · 🔀 88 · 📦 70 · 📋 35 - 68% open · ⏱️ 24.06.2022):

	```
	git clone https://github.com/rwl/PYPOWER
	```
- [PyPi](https://pypi.org/project/PYPOWER) (📥 2.5K / month):
	```
	pip install PYPOWER
	```
- [Conda](https://anaconda.org/anaconda/pypower):
	```
	conda install -c anaconda pypower
	```
- [Docker Hub](https://hub.docker.com/r/hwanghust/pypower) (📥 16 · ⏱️ 19.05.2019):
	```
	docker pull hwanghust/pypower
	```
</details>
<details><summary><b><a href="https://www.gridpath.io/">GridPath</a></b> (🥉17 ·  ⭐ 63) - Power system planning and operations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-marble/gridpath) (👨‍💻 7 · 🔀 25 · 📥 380 · 📋 300 - 20% open · ⏱️ 21.06.2022):

	```
	git clone https://github.com/blue-marble/gridpath
	```
</details>
<br>

## Optimizer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://highs.dev/">HiGHS</a></b> (🥇23 ·  ⭐ 420) - High performance serial and parallel solver for large scale sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ERGO-Code/HiGHS) (👨‍💻 44 · 🔀 86 · 📦 5 · 📋 340 - 14% open · ⏱️ 29.11.2022):

	```
	git clone https://github.com/ERGO-Code/HiGHS
	```
- [PyPi](https://pypi.org/project/scikit-highs) (📥 17 / month):
	```
	pip install scikit-highs
	```
</details>
<br>

## Machine/Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://l2rpn.chalearn.org/">Grid2Op</a></b> (🥇20 ·  ⭐ 200) - A testbed platform to model sequential decision making in.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rte-france/Grid2Op) (👨‍💻 21 · 🔀 82 · 📋 230 - 20% open · ⏱️ 05.07.2022):

	```
	git clone https://github.com/rte-france/Grid2Op
	```
- [PyPi](https://pypi.org/project/Grid2Op) (📥 460 / month):
	```
	pip install Grid2Op
	```
- [Docker Hub](https://hub.docker.com/r/bdonnot/grid2op) (📥 8.2K · ⭐ 1 · ⏱️ 05.07.2022):
	```
	docker pull bdonnot/grid2op
	```
</details>
<br>

## Power System Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://ourworldindata.org/energy">Data on Energy</a></b> ( ⭐ 140)  - Data on energy by Our World in Data. <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>

🔗&nbsp;<b><a href="https://github.com/tamu-engineering-research/COVID-EMDA">COVID-EMDA</a></b> ( ⭐ 53)  - Cross-Domain Data Hub with Electricity Market, Coronavirus Case, Mobility and.. <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code>

<br>

## Co-Simulation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Infrastructure for Co-Simulation_

<details><summary><b><a href="https://precice.org/">precice</a></b> (🥇23 ·  ⭐ 480) - Partitioned multi-physics simulations. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/precice/precice) (👨‍💻 46 · 🔀 130 · 📥 13K · 📋 620 - 24% open · ⏱️ 30.11.2022):

	```
	git clone https://github.com/precice/precice
	```
- [PyPi](https://pypi.org/project/pyprecice) (📥 210 / month):
	```
	pip install pyprecice
	```
- [Conda](https://anaconda.org/anaconda/pyprecice):
	```
	conda install -c anaconda pyprecice
	```
- [Docker Hub](https://hub.docker.com/r/precice/precice) (📥 8.2K · ⏱️ 10.08.2022):
	```
	docker pull precice/precice
	```
</details>
<details><summary><b><a href="https://helics.org/tools/">HELICS</a></b> (🥉22 ·  ⭐ 83) - Large-scale Infrastructure Co-Simulation. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GMLC-TDC/HELICS) (👨‍💻 37 · 🔀 33 · 📥 16K · 📋 600 - 12% open · ⏱️ 21.10.2022):

	```
	git clone https://github.com/GMLC-TDC/HELICS
	```
- [PyPi](https://pypi.org/project/helics) (📥 950 / month):
	```
	pip install helics
	```
- [Conda](https://anaconda.org/anaconda/helics):
	```
	conda install -c anaconda helics
	```
</details>
<br>

## Gas

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Gas Network Simulation_

<details><summary><b><a href="https://www.pandapipes.org/">pandapipes</a></b> (🥇21 ·  ⭐ 65) - A pipeflow calculation tool. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.python.org/static/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/e2nIEE/pandapipes) (👨‍💻 13 · 🔀 33 · 📦 6 · 📋 90 - 54% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/e2nIEE/pandapipes
	```
- [PyPi](https://pypi.org/project/pandapipes) (📥 1.5K / month):
	```
	pip install pandapipes
	```
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Geographical Visualization for Power Grid_

<details><summary><b><a href="https://www.nrel.gov/analysis/siip.html">PowerGraphics</a></b> (🥇12 ·  ⭐ 19 · ➕) - Visualization Program for PowerSimulations; Part of the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuliaLang/julia-logo-graphics/blob/master/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NREL-SIIP/PowerGraphics.jl) (👨‍💻 9 · 🔀 8 · 📋 29 - 31% open · ⏱️ 17.11.2022):

	```
	git clone https://github.com/nrel-siip/powergraphics.jl
	```
</details>
<br>

## Messaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Messaging Environment for Distributed Computation_


---

## Related Resources

- [**Papers With Code**](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/jinningwang/best-of-ps/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/jinningwang/best-of-ps/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/jinningwang/best-of-ps/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/jinningwang/best-of-ps/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/jinningwang/best-of-ps/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
