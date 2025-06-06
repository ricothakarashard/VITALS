# Prerequisites

To follow along during the workshop, or to run through the notebooks contained within the repository using the Openscapes 2i2c Cloud JupyterHub (cloud workspace), the following are required. All software or accounts are free.

1. **Earthdata Login account**  
    - Create an Earthdata Login account (if you don't already have one) at <https://urs.earthdata.nasa.gov/users/new>
    - Remember your username and password; you will need them to download or access data during the workshop and beyond.
2. **Netrc file**
    - This file is needed to access NASA Earthdata assets from a scripting environment like Python.
    - There are multiple methods to create a .netrc file. For this workshop, `earthaccess` package is used to automatically create a netrc file using your Earthdata login credentials if one does not exist. There are detailed instruction available for creating a .netrc file using other methods [here](https://github.com/nasa/LPDAAC-Data-Resources/blob/main/guides/create_netrc_file.md).
3. **Laptop or tablet**
    - Participation in the exercises requires a laptop or tablet. Yes, a tablet works too! All workshop participants will have access to a 2i2c Jupyter Lab instance running in AWS us-west 2.  

We recommmend creating a GitHub account (if you don’t already have one) at <https://github.com/join> to [contribute](../CONTRIBUTING.md) to this repository. Follow optional [advice on choosing your username](https://happygitwithr.com/github-acct.html).