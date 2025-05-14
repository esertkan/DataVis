
Post-common envelope binaries are of particular interest to astronomers due to their potential to host first or secondary generation planets. These binary star systems, in which one star has expanded and engulfed its companion during their evolution, can lead to unique planetary formation scenarios. To further our understanding of these intriguing systems, we have developed the CuPS-ETV (Catalogue of Circumbinary Planets Discovered with the ETV Technique), a comprehensive and easily accessible catalog, organized for structured queries and visualizations, enabling potential population analyses of such systems, their complex dynamics and evolution. The catalog is a compilation of system, stellar, and planetary companion properties based on multiple literature resources.

File: CuPS-ETV-datavis.jpynb

This repository contains a Jupyter Notebook that showcases example visualizations created using the CUPS-ETV(Circumbinary Planet System Catalog CUPS.excel) dataset. The notebook demonstrates related to circumbinary systems, can be explored using Python.

All plots are generated with the CUPS-ETV dataset

1. Hertzsprung-Russell Diagram for PCEB Host and Companion Stars

This plot illustrates where host stars ("A") and their secondary companions ("B") in Post-Common Envelope Binary (PCEB) systems are located on the Hertzsprung-Russell (HR) diagram.  
Since the CUPS-ETV catalog doesn't include luminosity directly, it is calculated using the Stefan-Boltzmann law from average temperature and radius values. Host and secondary stars are grouped and color-coded based on their effective temperature. This helps us understand the stellar evolution stage of each component.

---

2. 

This plot compares CUPS-ETV planets with those in the NASA Exoplanet Archive. Orbital periods and planetary masses are shown in log-log scale to visualize the detection space of different discovery methods (Transit, Radial Velocity, Imaging).  
CUPS-ETV planets are highlighted in a distinct color to show where they fall in the parameter space, helping evaluate how unique or typical these systems are relative to known exoplanets. 


---

3. System Contribution Frequency Chart

This stacked bar chart shows how many systems in the CUPS-ETV catalog have data in the planet, star, and system sections. Custom system names were manually applied to make the chart more readable.  
This visualization helps identify which systems are well-studied in terms of planetary data versus stellar or orbital system parameters.
---

📝 Note

for all figures we use  Python libraries such as Pandas, NumPy, and Matplotlib.  
The notebook aims to provide a clean and reproducible way to interact with the CUPS-ETV dataset for scientific exploration and outreach.

