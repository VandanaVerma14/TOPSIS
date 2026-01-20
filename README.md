📊 TOPSIS Decision Support System

This repository implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method as a complete decision-support system.
The project provides three different interfaces to use TOPSIS:

Command Line Application

Python Package

Web Application

🔍 Methodology

flowchart LR
    A[Data Input<br/>(CSV File)]
    B[Data Validation<br/>(Numeric Values,<br/>Weights & Impacts Check)]
    C[Normalization &<br/>Weight Application]
    D[Ideal Solution<br/>Determination<br/>(Best & Worst)]
    E[Ranking & Result<br/>Generation<br/>(Table & Graph)]

    A --> B --> C --> D --> E
