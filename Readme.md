# **TechPlots for PMOS and NMOS Transistors**

This repository contains detailed plots for PMOS and NMOS transistors, illustrating critical relationships under varying gate voltage (**Vg**) and channel length (**l**). These plots serve as a reference for transistor-level design and analysis.

### Technology node: gpdk045 PDK

### Link for the Project Report:
[ACMOS Project Report](https://github.com/nikhil2001-create/ACMOS_Project/blob/main/Acmos_report_final.pdf)

---

## **Simulation Variables**

- **Gate Voltage (Vg):** 0V to 1V (0.01V linear step)  
- **Channel Length (l):** 45nm to 540nm (45nm linear step)  

---

### Why Techplots Over the Square Law Model?

The square law model is a simplified analytical approach for MOSFET behavior, assuming idealized conditions. While it is useful for quick hand calculations, it lacks accuracy under practical scenarios like short-channel effects, velocity saturation, and other second-order phenomena that dominate in modern submicron technologies.

Techplots, derived from simulation data using technology files (e.g., GPDK180), provide a more realistic insight into MOSFET performance. They account for non-idealities and accurately model parameters such as (g_m), (f_t), and (g_m * r_o) across different operating points. These plots allow designers to optimize circuits more effectively, ensuring performance aligns with real-world fabrication.

In essence, techplots bridge the gap between theory and actual silicon behavior, making them indispensable for modern analog CMOS design.


## **Plots**

### **NMOS Plots**

1. **gm * ro vs gm/Id:** 
 
   ![n_gmro](https://github.com/user-attachments/assets/423c5b25-a60a-4cc6-8b93-fdc884708c2b)



2. **ft vs gm/Id:**  

   ![n_ft](https://github.com/user-attachments/assets/828b7f8c-3fb5-4ddb-a03e-7b07a6c6dc2f)



3. **Id/w vs gm/Id:**  

   ![n_idw](https://github.com/user-attachments/assets/429bb916-59e5-4bdf-96b4-976c5cec9725)


---


### **PMOS Plots**

1. **gm * ro vs gm/Id:**  

  ![p_gmro](https://github.com/user-attachments/assets/dabe9cf4-39cb-4149-8d42-e01eb3460c0a)


  
2. **ft vs gm/Id:** 
 
  ![p_ft](https://github.com/user-attachments/assets/a616c5f5-5c1e-468d-a8f1-9a5bb463dfe8)



3. **Id/w vs gm/Id:**  

  ![p_idw](https://github.com/user-attachments/assets/3278db93-adb9-4d25-b757-e0eb6f8fad2d)

     


---








