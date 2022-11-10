* Disclamer, README written in Markdown, may not be readable outside Github or other .md viewer.

# File hierarchy:

* **lab_2** - this is the main folder reffered in paths as ```~/```
  * **Original Data** - folder containing original importable data
    * ```billboard.csv``` - original data file
    * **Meta** - metadata folder
      * ```Metadata.txt``` - main metadata document
  * **Docs** - documents
    * ```Readme.md``` - readme file ***<- YOU ARE HERE***
    * ```Analisys.md``` - final analysis
    * ```Data appendix.md``` - data appendix file
  * **Scripts** - all executable scripts folder
    * ```mainTidy.ipynb``` - script generating data for analisys
    * ```analisysScript.ipynb``` - script generating analisys report
  * **Analisys Data** - folder containing data ready to be analysed
    * ```analisysData_1.csv``` - main data used for analysis

* The file hierarchy has to be mainianted in order to correctly run scripts

# Install guide

**1. Make sure conda is installed :**

```conda -V```

You can reffer to http://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

**2. Install packages :**
```
ipython>=4.1.2
jupyter>=1.0.0
matplotlib>=1.5.1
notebook>=4.1.0
numpy>=1.10.4
pandas>=0.17.1
seaborn>=0.7.0
q>=2.6
python-dotenv>=0.5.0
watermark>=1.3.0
pytest>=2.9.2
scikit-learn
scipy
```

# Run guide
1. Navigate to ``~/Scripts``
2. Execute ```jupyter-notebook``` in bash terminal
3. In order to generate processed data run ```mainTidy.ipynb```. Creates new ```analisysData_1.csv``` file at ```~/Analisys Data/```.
4. After generating data you can run ```analisysScript.pynb``` to generate ```Analisys.md``` report file.
