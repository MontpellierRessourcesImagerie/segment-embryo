# segment-embryo

[![License MIT](https://img.shields.io/pypi/l/segment-embryo.svg?color=green)](https://github.com/MontpellierRessourcesImagerie/segment-embryo/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/segment-embryo.svg?color=green)](https://pypi.org/project/segment-embryo)
[![Python Version](https://img.shields.io/pypi/pyversions/segment-embryo.svg?color=green)](https://python.org)
[![tests](https://github.com/MontpellierRessourcesImagerie/segment-embryo/workflows/tests/badge.svg)](https://github.com/MontpellierRessourcesImagerie/segment-embryo/actions)
[![codecov](https://codecov.io/gh/MontpellierRessourcesImagerie/segment-embryo/branch/main/graph/badge.svg)](https://codecov.io/gh/MontpellierRessourcesImagerie/segment-embryo)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/segment-embryo)](https://napari-hub.org/plugins/segment-embryo)

<img src="https://github.com/user-attachments/assets/4459f48c-435f-489d-b27c-25a4ea390871" align='left' width="30%"></img> 3D Segment ascidian embryos using cellpose. The images are first rescaled to be isotropic and then downscaled, before cellpose is used. The resulting labels are upscaled to match the original data.

----------------------------------

This [napari] plugin was generated with [copier] using the [napari-plugin-template].

<!--
Don't miss the full getting started guide to set up your new package:
https://github.com/napari/napari-plugin-template#getting-started

and review the napari docs for plugin developers:
https://napari.org/stable/plugins/index.html
-->

## Installation

You can install `segment-embryo` via [pip]:

    pip install segment-embryo




## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [MIT] license,
"segment-embryo" is free and open source software

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[napari]: https://github.com/napari/napari
[copier]: https://copier.readthedocs.io/en/stable/
[@napari]: https://github.com/napari
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[napari-plugin-template]: https://github.com/napari/napari-plugin-template

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
