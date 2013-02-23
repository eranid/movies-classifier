This is the result of the assignment you guys gave me.

1. I wrote the research as an Ipython notebook. That way you can see the research and the code together.

2. This kind of writing is great for research, less so for production. I took this into account to speed up the development.

3. Obviously for production this needs to be encapsulated, packaged and maybe a little object-oriented :)

4. You don't need to run anything, except do the following:

	- make sure you are running python 2.7(.3)
	- make sure you have ipython installed (sudo apt-get install ipython)
	- make sure you have the LATEST(at least 0.13 i think, 0.14 is the current) notebook installed (see http://ipython.org/ipython-doc/dev/interactive/htmlnotebook.html ):
		- The following should do it:
		>> sudo apt-get install python-zmq libzmq libzmq-dev
		>> sudo easy_install ipython[zmq,qtconsole,notebook,test]
	- in the src folder of this repository, run:
		>> ipython notebook --pylab
	- a browser window should open up, choose the movies notebook
	- now you can just read the research and see the code. It walks you through my mental and dev process, culminating in the classification of the test_movies.json file.

5. If you are itching to run it yourselves, you can do that, just make sure you have everything installed to comply with the "
imports" in the first cell.
The needed import are (most are inherent in python 2.7)

json
pprint
time
nltk
collections
pickle
re
numpy (that is kind of a pickle if you dont have it, as it does not come with python automatically. sudo apt-get install python-numpy should do it I think.)
os

6. If you are runnint it yourselves, ge patient, the whole thing can take up to 15 minutes i'd say, to train the classifiers.


That's it.
Thanks, it's been a REALLY interesting little project...
