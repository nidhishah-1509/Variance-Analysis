<h1>Variance Analysis Tool</h1>
<h2>Introduction</h2>
The Material Variance Analysis project is a web-based tool designed to help users evaluate material price, usage, mix, and yield variances in manufacturing. It provides an interactive calculator where users can input standard and actual prices and quantities for different materials to analyze cost deviations and identify inefficiencies. <br> <br>

This project aims to enhance material cost control by computing key variances. Price variance measures the impact of price fluctuations, usage variance highlights differences in material consumption, mix variance assesses proportional changes in material combinations, and yield variance evaluates output efficiency based on inputs.  <br> <br>

The user interface is clean and intuitive, featuring a dropdown selector for choosing the number of materials. Users enter the required values, and JavaScript functions dynamically compute and display variances. The tool also allows for report generation, enabling users to download a summary of their analysis in PDF format. <br> <br>

This project is beneficial for manufacturing firms analyzing production efficiency, accounting and finance students learning about variance analysis, and small businesses aiming for better cost control and budgeting. By integrating financial analysis with web development and automation, this tool provides a practical solution for improving decision-making in material cost management. <br> <br>

<h2>Main Features</h2>
1. Material Variance Analysis <br>
    - Supports up to 4 materials. <br>
    - Calculates: Price Variance, Usage Variance, Mix Variance, Yield Variance <br>
    - Generates downloadable PDF report. <br>
2. Labor Variance Analysis <br>
    - Handles Skilled, Semi-skilled, and Unskilled labor.<br>
    - Calculates: Rate Variance, Cost Variance, Efficiency Variance, Idle Time Variance  <br>
    - Dynamic UI adapts based on number of labor types.
    - One-click PDF report export.
3. Navigation-Enabled UI<br>
    - Fully styled with a modern layout and responsive grid.<br>
    - Navigation bar links across: index.html (Home), material_variance.html, labor_variance.html<br>

<h2>Structure</h2>
.<br>
├── index.html             # Home page with variance descriptions <br>
├── material_variance.html # Material variance calculator<br>
├── labor_variance.html    # Labor variance calculator<br>
├── stock-market.jpg       # Optional background image<br>
└── README.md              # Project documentation<br>

<h2>Tech Stack</h2>
- HTML5 – Markup structure <br>
- CSS3 – Responsive layout and grid design <br>
- JavaScript – Dynamic DOM manipulation and calculations <br>
- jsPDF – PDF export library <br>

<h2>Sample Usage Flow</h2>
<h3>Material Price Variance</h3>
Formula: (Standard Price − Actual Price) × Actual Quantity
Example Output: Price Variance for Material 1: 120.00 Rs. (A)

<h3>Labor Rate Variance</h3>
Formula: (Actual Rate − Standard Rate) × Actual Hours
Example Output: Skilled Labor: Rate Variance: -100.00

<h2>Future Improvements</h2>
- Add graphical charts (bar/pie) for visual variance representation.<br>
- Save historical entries to browser localStorage.<br>
- Add validation and tooltips for input guidance..<br>
- Create a mobile app version.<br>

<h2>Contributions</h2>
Made by:
Arpita, Ishaa, Nidhi, Pavarna, Saanvi <br>

<h2>License</h2>
This project is built for academic/educational purposes.
Feel free to use, modify, and distribute with attribution.<br>
