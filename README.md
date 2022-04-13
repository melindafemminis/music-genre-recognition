# Music Genre Recognition

This project was built to recognize an audio file's musical style with machine learning algorithms. It was trained on the [GTZAN Dataset](http://marsyas.info/downloads/datasets.html) that contains an equal number of 30 seconds tracks for a few predetermined musical styles. 

We used logistic regression, K-nearest neighbors, Random forest and Kernel SVM algorithms and [Flask](https://flask.palletsprojects.com/en/2.1.x/)/[Heroku](https://www.heroku.com) to deploy the project.

## Test it online !

It is accessible online: https://the-mgr-project.herokuapp.com.
For best results, only use 30 seconds .wav audio files. 


## Run it locally

1. Download the repository
2. Open the terminal and navigate to the flask directory: `$ cd users/yourusername/flask`
3. *optional but recommended: activate a virtual environement*
4. Run `$ pip install -r requirements` to install dependencies
5. Run `$ flask run` and follow the link to open Music Genre Recognition in your brower


## Further develpments

While we not actively working on this project anymore, we thought about a few more things to do that would improve it: 

- Restrict file input to .wav files only. Allowing other file types such as .pdf and .csv is confusing
- Add support for .mp3 audio files, which are also common
- Add audio visualization of the chosen file


*Music Genre Regonition is developed by Jason Ola, Andrei Anikin and Melinda Femminis during the semester of spring 2021 for the course "Développement logiciel" given by Davide Picca at the University of Lausanne.*
