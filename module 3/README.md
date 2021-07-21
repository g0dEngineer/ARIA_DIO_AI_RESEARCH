
 Artificial Intelligence Vehicle Sketch to Paint Converter | Aria Dio Automobile Ai Research
 ===========
 
 Author: God Bennett
 
![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_2.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_1.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_3.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_0.png)


Main Dio Ai Research Page
=========
https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research#3-artificial-intelligence-vehicle-sketch-to-paint-converter


Sketch Credits - Input image sketches used in Ai app
===========

Aria Dio 2045

* [Hand drawn sketch by God Bennett](https://www.facebook.com/TheAriaDio/posts/124979279493593)

BMW Input Sketch Credits:

* Unkown artist

Aston Martin Input Sketch Credits:

* [Official Aston Martin Concept Sketch](https://www.facebook.com/astonmartin/posts/10158041272118355)



Original repository:
===========
https://github.com/irfanICMLL/Auto_painter_demo





Setup demo:
===========

Follow all instructions in original repo, starting with my instructions below (So ignore the section on [the original repo](https://github.com/irfanICMLL/Auto_painter_dem) about requirements, but [focus on the pre-trained model download section](https://github.com/irfanICMLL/Auto_painter_demo#quick-start) ):

Overall setup (States specified versions that original readme did not specify when it comes to non-anaconda/direct traditional installation. Diverging from these have caused interdependency errors, although a large anaconda install could avert these issues as the original readme advises):

1. Py35 fresh install
2. Uninstall pip
3. Install setuptools 50.0.0 from zip file/Pypi site
4. Install pip-20.3.4 from zip file/Pypi site
5. pip install tornado==4.1
6. pip install urllib3==1.15
7. pip install Numpy==1.17.5
8. pip install scikit_image==0.15.0
9. pip install scipy==1.0.0
10. pip install werkzeug
11. pip install flask





Run demo:
===========


1. Open cmd.

2. Set python path to py35
path=C:\Users\18765\AppData\Local\Programs\Python\Python35

3. navigate to project folder.
cd C:\....\Auto_painter_demo-master

4. Create "result" folder to static folder in "Auto_painter_demo-master". This is missing from original repo for some reaosn, and app complains without it.

5. run Auto_painter_demo app and wait for model load and final report of port:
python app2.py

6. In browser, run final app in browser (chrome), at port number reported in step (4), by copying the line below, and pasting it in browser and hitting enter.
http://localhost:PORT_NUMBER_FROM_4

EG: http://localhost:10086

