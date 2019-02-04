# Prairie

*note: development of Prairie is currently paused/stop*

Prairie is a **visual programming** environment aimed at scientists and engineers. It's an **experiment** that tries to provide a natural and intuitive interface for **visualing** and **interacting** with complex data processing pipelines developped in **Python**.

<p align="center">
  <img src ="doc/scan_oct_example.gif"/>
</p>



## Overview

**Prairie** is neither meant to replace traditional IDEs nor develop pipelines from scratch. Instead, it is designed as a **functional tool** that goes on top of your **libraries, class, functions** and complement your pipelines with rich and extandable **interactive widgets**.

Main features include:

- Draging and dropping your existing class/functions **directly from your python files**

<p align="center">
  <img src ="doc/functions.gif" />
</p>

- Using interactive widgets to **interact with your data** : 



<div style='display:flex;flex-direction:row;align-items:center;justify-content:center;'>
        <div align='center'>
    	<img src="doc/inputs_and_outputs.png">
        <p><i>Code blocks</i></p>
   	</div>
    <div align='center'>
        <img src="doc/plot.png">
        <p><i>Plot block (using plotly)</i></p>
    </div>
<div>

<div style='display:flex;flex-direction:row;align-items:center;justify-content:center;'>
    <div align='center'>
        <img src="doc/matrix.png">
        <p><i>Matrix block</i></p>
    </div>
    <div align='center'>
    	<img src="doc/image_airy.png">
        <p><i>Image block</i></p>
   	</div>
<div>

- **and much more** (Prairie comes with an API to create custom blocks) ...



## Blocks and Widgets libraries

### Libraries

*note: Library extension features is not included in the current git version*

**Prairie** comes with out-of-the-box **block libraries** that can be extended with **custom and community-made libraries** and blocks. Libraries can be installed **like python packages**:

```shell
pip install prairie-<library-name>
# or
pipenv install prairie-<library-name>
```

and then become available on the interface, **loaded with your python interpreter** (pipenv/ virtualenv are advised).

### Default set

See the [features list](Features list.md) and the [prairie blocks icons](prairie-icons.md) files to learn more about default blocks included when installing Prairie



<p align="center">
  <img src ="doc/blocks-icons.png"/>
    <p align="center"><i>some Prairie block icons</i></p>
</p>