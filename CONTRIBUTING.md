# Contributing
At your first contribution do not forget to add your name and contact information to the README.md file

## Using GitHub
1. Fork the repository
2. Clone your fork
3. Unzip the virtual environment `devenv.zip` to the root of the project as `devenv`
4. Launch the virtual environment by opening a command line in the project folder and typing the command .\devenv\Scripts\activate (Windows) at the root of CoderDojoActivities, Mac and Linux will probably use ./devenv/Scripts/activate
5. Launch Jupyter by typing `jupyter notebook` in the same command line (you must have the virtual environment activated)


### Creating a new activity
An activity is supposed to be: fun, interactive and accessible.

Do not forget to add information at the beginning of the activity such as the authors (yourself?).
If your activity assumes that the persons have completed some other activities before, please add that information as well.
If you have to use new libraries use the `pip install` command and install them in devenv, then zip the folder again and replace the existing zipped folder.

We zip the virtual environment to allow

#### Installed at the moment:
* matplotlib
* numpy
* pandas
* Pillow
* wordcloud

### Changing an existing activity
If you plan on improving an existing activity, open the activity under /solutions (using Jupyter!) and do the changes there but do not forget to replicate those changes in /activities as it is the activity that will be used during the session!

### Supporting multiple languages
If you are planning on translating the activities it is great! Please create these under a new folder

In that case, please translate the README.md as well 

Example (for french):

/solutions/fr/MyTranslatedActivity.ipynb
/activities/fr/MyTranslatedActivity.ipynb
