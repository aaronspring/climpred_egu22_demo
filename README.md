# `climpred` demo for EGU22

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aaronspring/climpred_egu22_demo/HEAD?labpath=EGU22.ipynb)

Demo of [`climpred`](https://climpred.readthedocs.io/en/stable/) at the [European Geoscience Union 22 conference (EGU22)](https://www.egu22.eu/#)  calculating [Nino3.4](https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni) skill for [NMME hindcasts](http://iridl.ldeo.columbia.edu/expert/SOURCES/.Models/.NMME/) verified against [NOAA OISST observations](http://iridl.ldeo.columbia.edu/SOURCES/.NOAA/.NCEP/.EMC/.CMB/.GLOBAL/.Reyn_SmithOIv2/.monthly/.sst/)

Presentation details
--------------------

Presentation Title: [`climpred`: weather and climate forecast verification in python](https://meetingorganizer.copernicus.org/EGU22/EGU22-8200.html)

Aaron Spring | Thursday, 26 May 2022 15:24–15:31 | Room 0.94/95 | Vienna

Abstract: [EGU22-8200](https://meetingorganizer.copernicus.org/EGU22/EGU22-8200.html)

---

Session: [NP5.1 Advances in statistical post-processing, blending and verification of deterministic and ensemble forecasts](https://meetingorganizer.copernicus.org/EGU22/session/42639)

Thursday, 26 May 2022, 15:00–17:00 | Presentations | 15:10–16:40 | Room 0.94/95 |

Abstract: [NP5.1](https://meetingorganizer.copernicus.org/EGU22/session/42639)


How to run
----------

- In your browser: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aaronspring/climpred_egu22_demo/HEAD?labpath=EGU22.ipynb)
- Locally in any [environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html): `pip install climpred` or `conda install climpred`
- Locally in `climpred-dev` [environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html):

    ```bash
    git clone https://github.com/aaronspring/climpred_egu22_demo
    cd climpred_egu22_demo
    conda env create -f environment.yml
    jupyter lab
    ```

Software
--------

- https://climpred.readthedocs.io/en/stable/


Data
----

- [Nino3.4](https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni)
- [NMME hindcasts](http://iridl.ldeo.columbia.edu/expert/SOURCES/.Models/.NMME/)
- [NOAA OISST observations](http://iridl.ldeo.columbia.edu/SOURCES/.NOAA/.NCEP/.EMC/.CMB/.GLOBAL/.Reyn_SmithOIv2/.monthly/.sst/)
