# FSDA  (Flexible Statistics Data Analysis) MATLAB toolbox

The FSDA MATLAB Toolbox provides statisticians, engineers, scientists, researchers, and financial analysts with a comprehensive set of tools to assess and understand their data. FSDA Toolbox software includes functions and interactive tools for analyzing and modeling data, learning and teaching statistics.
You can grasp the main features from the short video http://rosa.unipr.it/fsda_video.html
More details about the latest release can be found at
http://rosa.unipr.it/FSDA/release_notes.html


## Getting Started

You can start to familiarize with the FSDA toolbox in one of the following ways.

   A. Run the examples contained in files examples_regression.m or examples_multivariate.m or examples_categorical.m
   Notice that all examples are organized in cells;

   B. Run the tutorials in the FSDA Matlab help pages;

   C. Watch the videos in the Examples section of the FSDA Matlab help pages

   D. Read section "Introduction to robust statistics" or "Technical introduction to Robust Statistics" in the FSDA Matlab help pages

   E. Read "Function reference page" in the FSDA Matlab help pages

### Prerequisites

FSDA toolbox needs MATLAB at least release R2012a


### Installing

To install FSDA it is necessary to run the file installFSDA.m
This file will:
1) copy all the HTML FSDA documentation file inside in the path (MATLAB docroot)/FSDA
2) Add a set folders to your MATLAB path (this can be done at any moment by running file addFSDA2path.m)
3) Launch buildocsearchdb in subfolder (FSDA root)/helpfiles/pointersHTML
4) Install the apps

## Running the tests

A list of files containing a series of examples associated to regression, multivariate analysis, clustering and the analysis of categorical data can be found at:

examples_regression.m (examples_regression.mlx)
examples_multivariate.m (examples_multivariate.mlx)
examples
Explain how to run the automated tests for this system

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [MATLAB](http://www.mathworks.com/) - The web framework used??????


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Marco Riani** - *Initial work* - [MarcoRianiUNIPR](https://github.com/MarcoRianiUNIPR)
* **Domenico Perrotta** - *Initial work* - [MarcoRianiUNIPR](https://github.com/MarcoRianiUNIPR)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

The FSDA toolbox is beeing protected by a European Union Public Licence (EUPL) - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

We would like to thank the following people for contributions given to the software implementation, development and testing or with suggestions, help and support to the FSDA project:

Al Khudhairy Delilah (EC Joint Research Centre, Ispra, Italy)
Arsenis Spyros (EC Joint Research Centre, Ispra, Italy)
Atkinson Anthony C. (LSE, UK)
Azzini Ivano (Brilema, Milan, Italy)
Bini Matilde (Università Europea di Roma, Italy)
Grossi Luigi (University of Verona, Italy)
Gusmini Massimiliano (cfp bauer, Milan, Italy)
Laurini Fabrizio (University of Parma, Italy)
Insolia Luca (University of Pisa, Italy)
Solaro Nadia (University of Milan, Italy)
Zani Sergio (University of Parma, Italy)

The FSDA toolbox for MATLAB includes software developed by the following third parties:

1) selectdata: routine written by John D'errico that can be found in the Mathworks' page
http://www.mathworks.com/matlabcentral/fileexchange/13857.

2) clickableLegend: function written by Ameya Deoras downloadable from
http://www.mathworks.com/matlabcentral/fx_files/21799/1/clickableLegend.m

3) cascade: routine written by Isaac Noh downloadable from
http://www.mathworks.com/matlabcentral/fileexchange/16002-cascade
4) progressBar: routine written by Stefan Doerr, based on: parfor_progress written by Jeremy Scheff downloadable from
http://www.mathworks.com/matlabcentral/fileexchange/43872-progress-bar-for-matlab-loops--incl-parfor-
5) suplabel: routine written by Ben Barrowes downloadable from
http://www.mathworks.com/matlabcentral/fileexchange/7772-suplabel
