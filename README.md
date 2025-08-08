### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name string
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
john,101,low,2,male,250311
rosy,102,high,3,female,251665
charlie,103,medium,1,male,240238
pinky,104,low,5,female,200200
bob,105,high,2,male,240240
--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

Training Data Set - Employee Table

<img width="548" height="300" alt="Screenshot 2025-08-08 105123" src="https://github.com/user-attachments/assets/4134291b-8374-4cb3-b7ab-eebe6aadc737" />

Training Data Set - Weather Table

<img width="573" height="403" alt="image" src="https://github.com/user-attachments/assets/95a71bef-21d9-4a31-bf06-3366869c033b" />


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
Employee Table after adding new attribute ADDRESS:

<img width="732" height="300" alt="Screenshot 2025-08-08 105611" src="https://github.com/user-attachments/assets/c5405543-dfd5-47d2-96b9-93994c2e3f3d" />

Weather Table after adding new attribute CLIMATE:

<img width="683" height="437" alt="image" src="https://github.com/user-attachments/assets/dd233f9a-e534-42a1-a7e0-f766cc114845" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
Employee Table after removing attribute EXP:

<img width="966" height="308" alt="Screenshot 2025-08-08 105652" src="https://github.com/user-attachments/assets/b4223614-afc0-47ea-ad1f-546c938b25a8" />

Weather Table after removing attributes WINDY, PLAY:

<img width="959" height="468" alt="image" src="https://github.com/user-attachments/assets/17484b1a-0afc-4821-8915-af3b80dbb368" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

Employee Table after Normalizing ID, EXP, PHONE:

<img width="1210" height="319" alt="Screenshot 2025-08-08 105735" src="https://github.com/user-attachments/assets/4d79b155-3f74-44a7-819d-01e7db72e87b" />

Weather Table after Normalizing TEMPARATURE, HUMIDITY:

<img width="1204" height="508" alt="image" src="https://github.com/user-attachments/assets/d871a5ee-8ca9-4d50-b4b7-38944fca19d3" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
