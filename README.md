# Local Search - FIB-IA 2023-24 Q1  
**Grade Achieved**: **10.5/11**

## Instructions to Run the Code  

This repository contains the code for the Local Search practice assignment. Below are the steps to set up and run the code.

### Setup Instructions  

We used **Visual Studio Code** and configured a JSON file to execute all `.jar` files required for the project, including `AIMA.jar`, `Bicing.jar`, and any other necessary files.  

#### If using Visual Studio Code:  
1. After unzipping the `code.zip` file, navigate to:  
   `Lab -> dist -> AIMAexample-master`  
2. Locate the `.vscode` folder (it's hidden by default).  
3. In the `settings.json` file, update **line 4** to set the path to your own directory where `AIMAexample-master` is located.

#### If using a different IDE or environment:  
1. Move the `AIMAexample-master` directory to a location where your IDE can execute it.  
2. Adjust the configuration according to your environment.

### Important Notes:  
- By default, the submission parameters are set to the **final experiment** (the special experiment).  
- If you want to simulate transport costs, modify the **`profit()` heuristic function** in the `BicingBoard.java` class. Specifically, remove the `0` multiplier on the cost in **line 226**.

---

Let me know if you need further help setting this up!

