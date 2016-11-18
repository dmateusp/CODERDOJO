# Contributing

Any contribution should be done on the "dev" branch! The master branch will be updated once the activities are tested and validated.
At your first contribution do not forget to add your name and contact information to the README.md file

### Guide on contributing to Open Source projects:

http://blog.davidecoppola.com/2016/11/howto-contribute-to-open-source-project-on-github/

## Using GitHub

1. Fork the repository
2. Clone your fork
3. Download and install Anaconda3 https://www.continuum.io/downloads
4. Launch the Anaconda terminal (On Windows: Search Windows > Anaconda Prompt)
5. Launch the Jupyter activities by typing `jupyter notebook` in the console Anaconda terminal, this will open a website


### Creating a new activity
An activity is supposed to be: fun, interactive and accessible.

If the activity is under development (or it is just and idea) please use the issues feature!

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
