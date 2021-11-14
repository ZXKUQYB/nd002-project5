# Communicate Data Findings

This is a personal project which focuses on the *exploratory analysis* step in the entire data analysis process, as well as the *data visualization* practices which would play a big role in any data analysis task.

### Instructions

The project is composed of 3 separate Jupyter notebook files.

- [01_exploratory_analysis.ipynb](https://github.com/ZXKUQYB/nd002-project5/blob/main/01_exploratory_analysis.ipynb) : The beginning part of the project. All the program code written for the exploratory analysis and various plots/charts creation can be found here.
- [02_slide_deck_presentation.ipynb](https://github.com/ZXKUQYB/nd002-project5/blob/main/02_slide_deck_presentation.ipynb) : The presentation part of the project. This notebook is actually a slideshow template, and should be opened in **Classic Notebook** interface to configure the slideshow settings of all code cells before converting this notebook to a HTML slideshow. Notice that not all the plots/charts created in the previous notebook are presented here, only the emphasized ones.
- [03_summary_report.ipynb](https://github.com/ZXKUQYB/nd002-project5/blob/main/03_summary_report.ipynb) : The ending part of the project, which serves as a brief summary of both the exploratory analysis and the explanatory presentation.

Feel free to download any of the Jupyter notebook files listed above to have a look at the project contents, and the zipped CSV file in the [data](https://github.com/ZXKUQYB/nd002-project5/tree/main/data) directory if you want to run the program code.

Like previous projects, it is recommended to use a temporary Jupyter server offered by [Project Jupyter](https://jupyter.org/try) to setup a test run of these notebooks. Be sure to choose **JupyterLab** when you get your temporary Jupyter server, since it comes with all the Python modules needed for this project already installed. But of course, you can also run it in your own local environment instead, but the instructions to configure a local environment will not be covered here.

### Additional Information

In this repository, there are also some static, soft copies of the Jupyter notebook files, as well as a slideshow, both created in HTML format by using [nbconvert](https://nbconvert.readthedocs.io), which are provided for your convenience. You can see the results of the project directly online without running the program code, especially when you use some online preview services such as [GitHub & BitBucket HTML Preview](https://htmlpreview.github.io/) to render them.

### Issues

The HTML slideshow can be created by running the following command (make sure the [notebook](https://github.com/ZXKUQYB/nd002-project5/blob/main/02_slide_deck_presentation.ipynb) and the [template](https://github.com/ZXKUQYB/nd002-project5/blob/main/output_toggle.tpl) are both in the current directory) :

```sh
$ jupyter nbconvert 02_slide_deck_presentation.ipynb --to slides --template output_toggle
```

Notice that this output template will only work for nbconvert with its version number ranging from 5.4.1 to 5.6.1, which means you may need to upgrade/downgrade your currently installed version of nbconvert before attempting to generate a HTML slideshow. You can run the following commands if you need to do so :

```sh
$ /usr/bin/yes 2>/dev/null | pip uninstall nbconvert
$ /usr/bin/yes 2>/dev/null | pip install nbconvert==5.6.1
```

### License

The contents of this repository are covered under the [GNU General Public License v3.0](https://github.com/ZXKUQYB/nd002-project5/blob/main/LICENSE).
