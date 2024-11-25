# Karnaugh Map (K-Map) Solver
## **Overview**
This project is a Karnaugh Map (K-Map) Solver implemented in C++. It allows users to simplify Boolean expressions using Sum of Products (SOP) and Product of Sums (POS) forms. The tool takes user inputs for minterms or maxterms, processes them, and visually represents the K-Map in a 4x4 grid. Additionally, it outputs the simplified Boolean expression based on the provided inputs.
### Features
**Sum of Products (SOP) Mode:** Users can input minterms, which are processed to create a Boolean expression in SOP form. \
**Product of Sums (POS) Mode:** Users can input maxterms, which are processed to generate a Boolean expression in POS form. \
**K-Map Visualization:** The program displays a 4x4 K-Map grid with the user inputs. \
**Boolean Expression Output:** Based on the K-Map, the program provides a simplified Boolean expression for both SOP and POS. \
### File Structure \

**main.cpp:** The main file containing all the logic for K-Map visualization, SOP, and POS calculations.
**Functions include:**
**adjustMinterm:** Adjusts specific minterms for K-Map grid placement. \
**adjustMaxterm: **Adjusts maxterms for K-Map representation. \
**printKMap: **Displays the K-Map for SOP. \
**printKMapPOS**: Displays the K-Map for POS. \
A simple menu-driven interface guides users through the process. \

## How It Works
### SOP Mode:

User inputs the desired number of minterms. \
Each minterm is adjusted if necessary for accurate K-Map placement. \
The program creates a 4x4 K-Map grid with the minterms. \
A simplified Boolean expression is printed in SOP form. \
### POS Mode: \
User inputs the desired number of maxterms. \
Each maxterm is adjusted for accurate K-Map placement. \
The program creates a 4x4 K-Map grid with the maxterms. \
A simplified Boolean expression is printed in POS form. \
