# Electrical-Datasets-Alkaline-Batteries

This repository contains the impedance spectroscopy and rest-voltage interval datasets used in the analysis presented in the paper:

*“Modeling of Alkaline Batteries and Investigation of the Relationship Between Electrochemical Impedance and Raman Spectroscopy,”*  
**Journal of Energy Storage**, 2026.

The paper is co-authored by Marzio Barresi, Simone Barcellona, Cha Long, Lorenzo Codecasa, Marco Menegazzo, Rossella Yivlialin, Eugenio Gibertini, Andrea Lucotti, Gianlorenzo Bussetti, and Samuele Grillo.

---

## Dataset description

This repository provides raw experimental impedance spectroscopy and rest-voltage interval data collected according to the battery test matrix reported in the paper.

---

## Impedance spectroscopy datasets

The following CSV files contain raw experimental data obtained from galvanostatic electrochemical impedance spectroscopy (GEIS) measurements performed on individual cells:

- `Cell_1_GEIS.csv`
- `Cell_2_GEIS.csv`
- `Cell_3_GEIS.csv`
- `Cell_4_GEIS.csv`
- `Cell_5_GEIS.csv`
- `Cell_6_GEIS.csv`
- `Cell_7_GEIS.csv`
- `Cell_8_GEIS.csv`
- `Cell_9_GEIS.csv`

### Data format (GEIS)

All GEIS datasets are provided in CSV format with the following columns:

- **SOC [%]** – Battery state of charge  
- **Voltage [V]** – Measured battery voltage  
- **Frequency [Hz]** – Excitation frequency  
- **Re(Ztot) [Ohm]** – Real part of the total battery impedance (Re(Ztot))  
- **-Im(Ztot) [Ohm]** – Negative imaginary part of the total battery impedance (-Im(Ztot))

---

## Rest-voltage interval datasets

The following CSV files contain rest-voltage interval data measured on individual cells:

- `Cell_2_REST.csv`
- `Cell_3_REST.csv`
- `Cell_4_REST.csv`
- `Cell_5_REST.csv`
- `Cell_6_REST.csv`
- `Cell_7_REST.csv`
- `Cell_8_REST.csv`
- `Cell_9_REST.csv`

### Data format (REST)

All rest-voltage interval datasets are provided in CSV format with the following columns:

- **SOC [%]** – Battery state of charge  
- **Time [s]** – Time interval  
- **Voltage [V]** – Measured battery voltage  

---

## Contact

For further information or assistance, please contact:  
- marzio.barresi@polimi.it  
- simone.barcellona@polimi.it

---

## License

This dataset is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.
