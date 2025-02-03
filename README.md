

---

# **Design and Analysis of Yagi-Uda Antenna using CST Microwave Studio**

## **Overview**
This project focuses on designing and analyzing a **Yagi-Uda antenna**, a type of directional antenna that consists of multiple elements: a driven element, reflector, and director(s). The goal is to optimize the antenna for a specific operating frequency, analyze its radiation pattern, and calculate performance metrics such as gain, directivity, and bandwidth using **CST Microwave Studio 2019 (Student Edition)**.

## **Aim**
The primary aim of this experiment is to:
- Design a **Yagi-Uda antenna** for a specific frequency.
- Optimize the antenna elements for maximum gain and directivity.
- Analyze the **radiation pattern**, **S-parameters**, and **bandwidth**.

## **Design Parameters**

### **Mathematical Calculation**

- **Operating frequency (f)**: 200 MHz
- Operating frequency (f) = 200 MHz

Wavelength (λ) = c / f
                = (3 × 10^8 m/s) / (200 × 10^6 Hz)
                = 1.5 m

Element Length Calculations:
- Driven Element (La):
  La = 0.416 m
  Scaled length: La = 0.416 × 1.5 = 0.624 m
  
- Director Element (Ly):
  Ly = 0.475 m
  Scaled length: Ly = 0.475 × 1.5 = 0.7125 m

Additional Element Lengths:
- L_a1 = 0.44 m
  Scaled length: L_a1 = 0.44 × 1.5 = 0.66 m
  
- L_a2 = 0.44 m
  Scaled length: L_a2 = 0.44 × 1.5 = 0.66 m

- L_a3 = 0.43 m
  Scaled length: L_a3 = 0.43 × 1.5 = 0.645 m

Spacing Between Elements:
- S = 0.251 m
- S = 0.375 m
- S = 0.311 m
  Scaled spacing: S = 0.31 × 1.5 = 0.465 m

Other Parameters:
- Spacing distance (d) = 0.011 m
- Element spacing (a) = 0.01 × 1.5 = 0.015 m

Length of Away:
Length = 1.5 × 15 = 2.25 m

## **Procedure**
### **Step 1: Setting Up CST Studio Suite**
1. Open **CST Studio Suite 2019 (Student Edition)**.
2. Create a **new project** and select **Antenna Design** as the template.
3. Set the working frequency to **2.4 GHz**.

### **Step 2: Designing the Yagi-Uda Antenna**
1. **Driven Element**: Define a half-wave dipole element with a length of 62.5 mm and a width of 3 mm.
2. **Reflector Element**: Design a reflector element with a length of 68.75 mm and place it 25 mm behind the driven element.
3. **Director Element(s)**: Design one or more director elements, each 56.25 mm long, and place them 25 mm in front of the driven element.
4. **Ground Plane**: Create a simple ground plane that spans the full width of the antenna array.
![image](https://github.com/user-attachments/assets/7b9ebd6c-3cd0-451d-af86-af01dd71f9e4)


### **Step 3: Simulation and Optimization**
1. Run an **S-parameter simulation** to analyze the reflection characteristics (S11 parameter).
2. Optimize the length and spacing of the reflector and director(s) to achieve the desired impedance matching and gain.
3. Perform a **radiation pattern simulation** to evaluate the antenna's directivity and beam width.

### **Step 4: Analyzing the Results**
1. Extract the **S11 parameter** to verify the impedance matching and bandwidth (reflection coefficient should be below -10 dB).
2. Analyze the **radiation pattern** to confirm the directional properties of the antenna.
3. Calculate the **gain** and **directivity** from the simulation results.
4. Evaluate the **bandwidth** from the S-parameters, considering the frequency range where the S11 remains below -10 dB.

![image](https://github.com/user-attachments/assets/cd1cd101-6d9a-49f6-8725-e51cb3cf24bd)

![image](https://github.com/user-attachments/assets/b40fae02-8b52-48e2-8dd6-16538c8ff869)


### **Step 5: Validation and Comparison**
1. Compare the theoretical results with the simulated results to ensure consistency.
2. Discuss the impact of element lengths, spacing, and the number of directors on performance.

## **Conclusion**
This project successfully demonstrates the design and analysis of a **Yagi-Uda antenna** in **CST Microwave Studio 2019**. By optimizing the antenna elements and evaluating the S-parameters and radiation patterns, this design achieves a good balance of high gain, directional properties, and optimal bandwidth.

## **Future Enhancements**
- **Array Configuration**: Explore the design of a Yagi-Uda array for further gain enhancement.
- **Multi-band Yagi-Uda**: Design the antenna to support multiple frequencies by varying the lengths and spacings of the elements.
- **Material Variation**: Analyze the effect of different substrate materials or element materials (e.g., copper, aluminum) on performance.

## **Acknowledgment**
We express our gratitude to the mentors and institutions that supported this project.

## **License**
This project is open-source and available under the **MIT License**.

---

