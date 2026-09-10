# A3 – Parametric Design & Finite Element Analysis

## Part 1 - Design
After first reading through the assignment, I started by writing out the equation for deflection due to direction tensile or compressive force. I confirmed that the units cancelled out to produce inches, and made two initial sketches of the scenario. I also wrote out the given parameters from the assignment.

I made the decision that the applied force would be 500 lbs, the width of the bar would be 0.500 inches, and Young’s Modulus for the bar would be 11.5x10^6 psi. After solving the deflection equation for length and plugging in my chosen values for F, e, A, and Young’s Modulus (E), I found that the length of the bar was going to be 40.64 inches. I thought that this was incorrect, so I changed my decision for the value of E, selecting 8.5x10^6 psi. The result of my calculations then was 30.0406 inches.

<img width="598" height="535" alt="image" src="https://github.com/user-attachments/assets/a0fb8fff-1f9d-4836-ad36-1b5d62f1b60a" />

## Part 2 - Finite Element Analysis
I found an “Aluminum Alloy“ with a modulus of 10.15x10^6 psi, and chose it. My calculations for the length of the bar came out to be 35.8720 inches. After doing the Finite Element Analysis, the “displacement” that solidworks calculated was 0.2284 mm.

<img width="2263" height="1215" alt="image" src="https://github.com/user-attachments/assets/fcbacb40-107e-46ad-aea8-01cb903cebda" />

Given that 1 inch is equal to 25.4 mm, the calculated displacement of 0.2284 was equal to 0.00899 inches, which is 1x10^-5 inches less than the maximum axial deflection given by the problem.

The following image is the Von Mises stress map for the bar:
<img width="2272" height="1237" alt="image" src="https://github.com/user-attachments/assets/45f206b1-f63d-4b97-a836-009a5a8a0c15" />

## Part 3 - Design Reflection
In my final iteration (where E = 10.15x10^6 psi), my hand calculations resulted in a length of 30.0406 inches with a maximum axial deflection of 0.009 inches. In the Finite Element Analysis in Solidworks, with a length of 30.0406 inches, the resulting axial deflection was 0.2284 mm which equals 0.00899 inches. The percent difference between my hand-calculated axial deflection and F.E.A. axial deflection was 0.1111%. 

## Part 4 


## Part 5 - Modifying Parameters

<img width="597" height="365" alt="image" src="https://github.com/user-attachments/assets/560d31f5-c7cf-409c-b4c9-5c3fc0b43948" />

<img width="774" height="572" alt="image" src="https://github.com/user-attachments/assets/cd7a5c8b-861c-4dc7-85a8-64c6d704a537" />

<img width="872" height="593" alt="image" src="https://github.com/user-attachments/assets/ca2cbeb0-c511-481f-9062-a5cc823bed73" />

<img width="875" height="588" alt="image" src="https://github.com/user-attachments/assets/7fbb5a3a-adc2-4889-a6c3-f4a84cde9994" />

Click here to download the Solidworks file: 
<a href="myFile.js" download>Click to Download</a>
