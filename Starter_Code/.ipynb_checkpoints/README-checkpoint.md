Mercado Libre Growth Analysis


This file analyzes the MercadoLibre's financial and user data in various methods to make the company grow. It determinds whether or not the ability to predict search traffic can translate into the ability to successfully trade the stock
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For data manipulation and analysis.
* [hvplot](https://hvplot.holoviz.org/) - For interactive user prompts and dialogs
* [pathlib](https://docs.python.org/3/library/pathlib.html) - To provide for an easier method to interact with the filesystem no matter what the operating system is.
* [prophet](https://facebook.github.io/prophet/) -  A fast and automated forecasting procedure that can be tuned by hand.
* [numpy](https://numpy.org/) -  A fundamental package for scientific computing with Python.
* [pystan](https://mc-stan.org/users/interfaces/pystan) - A software for facilitating statistical inference at the frontiers of applied statistics.



---

## Installation Guide

Before running the application first install the following dependencies.

``` pyviz
  conda install -c pyviz hvplot geoviews
```

``` prophet
    python -m pip install prophet
```

``` pystan(must be 2.19.1.1)
    pip install pystan==2.19.1.1
```

``` numpy
    pip install numpy
```


---

## 

In order to run this analysis, we use various tools from the prophet, pystan, numpy and hvplot library. Please use the following libraries to operate this notebook:

    from prophet import Prophet
    import hvplot.pandas
    import numpy as np
    import pystan

---

## Contributors

Brought to you by PShum FinTech Consulting

---

## License

+ Prophet
MIT

Copyright (c) Facebook, Inc. and its affiliates.

+ PyStan

ISC License

Copyright (c) 2017, pystan developers

+ Numpy

Copyright (C) 2008-2022 Stefan van der Walt <stefan@mentat.za.net>, Pauli Virtanen <pav@iki.fi>

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in
    the documentation and/or other materials provided with the
    distribution.
    
+ HvPlot    

License: BSD License (BSD)

+ Pandas

BSD 3-Clause License

Copyright (c) 2008-2011, AQR Capital Management, LLC, Lambda Foundry, Inc. and PyData Development Team
All rights reserved.

Copyright (c) 2011-2023, Open source contributors.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.