# Covid-19-Probability-Detector
Covid probability tester uses python and ML to tell you probability of having corona via asking 9 questions

To get this running in your pc first you must have python3.8 in your pc then download this repository then extract > shift + Right Click in folder > click open power shell window here > some dependences needed to be installed for that following commands needes to run respectively pip install pandas sklearn tensorflow, pip install pickle, pip install flask, pip install jupyter > then run python ./my training.py a pkl file gets created it is just a saved training model nothing to do with it then run python ./main.py > you will get a webserver address copy and paste that in any of browser you will get your website running then just fill in all answers and you will get the result.

The data used in this program is randomly generated so you will not get exact answer it is just a result base on random data.

Explaination: 
  main.py is main python file it starts the flask web server and runs to interconnect html and machine learning
  myTraining.py is a ML file which is used to understand and learn data and give result based on that after running myTraining.py a pkl file gets created which is saved learned model by ML.
  Data.csv is the file which has the randomly generated data which we are using to add in our model to test which can be further replaced with real data to get accurate results.
  The templates folder have html files whis is shown to you and static folder has all css.
  you can also write jupyter notebook or python -m notebook in power shell start jupyter notebook server and then open COVID tester.ipynb to see all rough data and code we used while making this program.
 
