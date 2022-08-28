# Left-Ventricle-Segmentation-A-Combination-of-Intelligent-Image-Enhancement-Techniques-and-Novel-

Proposed Flow:
![image](https://user-images.githubusercontent.com/25412736/187078610-8a323a20-f4f6-4031-a0a1-b52a57dce302.png)


The Proposed Appraoch is based on :
1.1	Data Preparation
![image](https://user-images.githubusercontent.com/25412736/187078651-af6f4a40-87ae-49df-bb12-98e9c9b2f5ea.png)


1.2.	Pre-processing

1.2.1.	Intelligent Contrast Stretching and Histogram Equalization
![image](https://user-images.githubusercontent.com/25412736/187078690-e0cf78ca-9087-47b2-a50f-5f4ebc9f18e5.png)
![image](https://user-images.githubusercontent.com/25412736/187078695-7a330e51-984c-4627-b0e0-e2c5f2fffc1f.png)


| Type of Image	| Feature	| Image 1 |	Image 2 |	Image 3 |
| --- | --- | --- | --- | --- |
|Low Contrast Image	| BinCounts	| 95	| 166 |	148 |
| BinEdges |	96	| 167 |	149 |
| BinLimits |	20 |	34 |	46 |
| High Limit |	210	| 200	 |	194	 |
| BinWidth |	2 |	1	|	1	|
| Normal Image |BinCounts	| 51 |	64 |	51 |
| BinEdges |	52 |	65 |	52 |
| BinLimits |	0 |	63 |	0 |
| High Limit  |	255 |	255 |	255 |
|	BinWidth |	5 |	3 |	5 |

Distribution of Images into Low Contrast and Normal Image

| Sr. No.|	Type |	Images |
|        |       | Total	| Low Contrast	| Normal |
| --- | --- | --- |
|: 1	  :|  Epicardium – Inner	| 7365 |	2495  |	4870  |
|: 2    :|	Endocardium - Outer	| 7365 |	2247  |	5118  |

