


Artificial Intelligence Vehicle Sketch to Paint Converter | Aria Dio Automobile Ai Research
===========
 

Author: [God Bennett](https://github.com/g0dEngineer)
===========

The future of automated/Ai based car design is exciting, even seeing my simple experiment below.

Configuring and using an open source Artificial Intelligence library for auto painting (that was not explicitly trained on car painting), I somewhat quickly experimented with vehicle painting/shading.

Results were surprising, the Ai being able to shade/paint sketches of vehicles, in seconds, without seeming to have been trained explicitly on the task of shading/painting vehicles.

Youtube Demo: 

https://www.youtube.com/watch?v=nt2RaTLBQQE

Dio Page
===========
https://www.facebook.com/TheAriaDio/


  
![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_2.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_1.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_3.png)

Some handrawn inputs by God Bennett:

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/0_large_cropped_lines.jpg | width=100)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/1_large_cropped_shaded.jpg | width=100)

God's inputs automatically painted:

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_0.png)

![image](https://github.com/g0dEngineer/Dio-Le-Automobile-Ai-Research/blob/main/module%203/RESULT_0b.png)



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

Follow all instructions in the excellent original repo, however, starting with my instructions below (So ignore the section on [the original repo](https://github.com/irfanICMLL/Auto_painter_dem) about requirements, but [focus on the pre-trained model download section](https://github.com/irfanICMLL/Auto_painter_demo#quick-start) ):

My overall setup (States specified versions that original readme did not specify when it comes to non-anaconda/direct traditional installation. Diverging from these have caused interdependency errors, although a large anaconda install could avert these issues as the original readme somewhat advises):

1. Python 3.5 fresh install
2. Uninstall pip
3. Install setuptools 50.0.0 from zip file/Pypi site
4. Install pip-20.3.4 from zip file/Pypi site
5. pip install tensorflow==1.4.0
6. pip install tornado==4.1
7. pip install urllib3==1.15
8. pip install Numpy==1.17.5
9. pip install scikit_image==0.15.0
10. pip install scipy==1.0.0
11. pip install werkzeug
12. pip install flask





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

