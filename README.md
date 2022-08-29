# Left-Ventricle-Segmentation-A-Combination-of-Intelligent-Image-Enhancement-Techniques-and-Novel-

Proposed Flow:
![image](https://user-images.githubusercontent.com/25412736/187078610-8a323a20-f4f6-4031-a0a1-b52a57dce302.png)


The Proposed Appraoch is based on :
##  1.1	Data Preparation
![image](https://user-images.githubusercontent.com/25412736/187078651-af6f4a40-87ae-49df-bb12-98e9c9b2f5ea.png)
<br>
##  1.2.	Pre-processing
<br>
1.2.1.	Intelligent Contrast Stretching and Histogram Equalization
![image](https://user-images.githubusercontent.com/25412736/187078690-e0cf78ca-9087-47b2-a50f-5f4ebc9f18e5.png)
![image](https://user-images.githubusercontent.com/25412736/187078695-7a330e51-984c-4627-b0e0-e2c5f2fffc1f.png)

<br>

| Type of Image	      | Feature	    | Image 1 |	Image 2 |	Image 3 |
| -----------         | ------      | ---     | ---     | ---     |
| Low Contrast Image	| BinCounts	  | 95	    | 166     |	148     |
                      | BinEdges    |	96	    | 167     |	149     |
                      | BinLimits   |	20      |	34      |	46      |
                      | High Limit  |	210	    | 200	    |	194	    |
                      | BinWidth    |	2       |	1	      |	1	      |
| Normal Image        |BinCounts	  | 51      |	64      |	51      |
                      | BinEdges    |	52      |	65      |	52      |
                      | BinLimits   |	0       |	63      |	0       |
                      | High Limit  |	255     |	255     |	255     |
                      |	BinWidth    |	5       |	3       |	5       |
<br>
Distribution of Images into Low Contrast and Normal Image
<br>
| Sr. No.|	Type |  Total | Low Contrast  |	 Normal Images |
| --- | --- | --- | --- | --- |
|: 1	  :|  Epicardium – Inner	| 7365 |	2495  |	4870  |
|: 2    :|	Endocardium - Outer	| 7365 |	2247  |	5118  |
<br>

##  1.3.	Proposed Model Design and Architecture

![image](https://user-images.githubusercontent.com/25412736/187079201-80dc5181-4e5e-40bb-8d97-af7f622830cc.png)


<br>
![image](https://user-images.githubusercontent.com/25412736/187079210-1071d264-7a97-4959-9c24-f46d714a277b.png)
<br>
# 2.  Results:
<br>
| --- | --- | --- | --- | --- | --- |
| Epochs  | Accuracy | Dice coefficient | 	IoU  | 	Loss | 	Precision | 
| 20	| 0.911231	| 0.9444	| 0.9506	| 0.0163	| 0.9959  |
| 25	| 0.9115	| 0.9568	| 0.9551	| 0.0146	| 0.9967  |
| 30	| 0.9116	| 0.9577	| 0.9567	| 0.0139	| 0.9973  |
| 35	| 0.9116	| 0.9598	| 0.9569	| 0.0138	| 0.9972  |
| 38	| 0.9116	| 0.9608	| 0.9570	| 0.0138	| 0.9973  |
| 40	| 0.9117	| 0.9645	| 0.9571	| 0.0137	| 0.9972  |
| 42	| 0.9117	| 0.9662	| 0.9571	| 0.0137	| 0.9973  |
| 51	| 0.9119	| 0.9682	| 0.9598	| 0.0132	| 0.9978  |
| 60	| 0.9270	| 0.9712	| 0.9673	| 0.0120	| 0.9980  |

<br>
![image](https://user-images.githubusercontent.com/25412736/187079412-3e607286-1d8c-4b68-852b-13ada6075498.png)
<br>

![image](https://user-images.githubusercontent.com/25412736/187079415-b7568d78-29b0-46d4-a65e-391ce0514d16.png)

<br>

![image](https://user-images.githubusercontent.com/25412736/187079428-3108750f-58ec-4401-bee7-9a75718c3162.png)

<br>
![image](https://user-images.githubusercontent.com/25412736/187079421-4b4b2c04-24b3-4584-950c-f88bb1bad477.png)
