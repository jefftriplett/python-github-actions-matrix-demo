# Python GitHub Actions Matrix Demo

This repository is an example of how to use [GitHub Actions Matrix feature](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#jobsjob_idstrategymatrix). 

Our demo installs Python versions 2.7, 3.5, 3.6, 3.7, and 3.8 and installed Django versions 1.11, 2.0, 2.1, 2.2, and 3.0 and uses the `matrix` feature to only install Django into Python versions which are supported. 

See the [Actions tab](https://github.com/jefftriplett/python-github-actions-matrix-demo/actions) for the results. 
