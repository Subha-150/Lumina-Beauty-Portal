Lumina Beauty & Grade Utility Portal
This repository contains a responsive web interface for Lumina Beauty, a high-end cosmetic brand, alongside a robust Python-based Grade Calculator.

💄 Lumina Beauty Web Interface
The web portion of this project demonstrates modern CSS layout techniques to create a luxury brand experience.

Key Features
Sticky Navigation: A horizontal navigation bar that stays fixed at the top while scrolling. Smooth Navigation: Uses anchor links (#home, #about, etc.) with smooth-scroll behavior to navigate between brand sections. Responsive Product Cards: A flexible grid of service and product cards that automatically re-arranges based on screen size.

Flexbox Implementation
CSS Flexbox powers the layout to ensure perfect alignment. Navigation: Uses display: flex and justify-content: space-between to separate the brand logo from navigation links. Card Alignment: The .card-container utilizes flex-wrap: wrap to allow elements to move to the next line on smaller screens. Centering: Each card utilizes internal flex properties (justify-content: center and align-items: center) to maintain content balance.

🎓 Academic Grade Calculator
Included in this repository is Grade_calculator.py, a Python utility for student performance analysis.
Marks,Grade,Status Message
90 - 100,A+,Excellence achieved!
80 - 89,A,Great job!
70 - 79,B,Cleared comfortably
50 - 69,C,Passed
40 - 49,D,Marginal Pass
< 40,F,Please seek counseling

Features
Input Validation: Handles invalid marks (outside 0-100) and non-numeric entries using error handling. Business Logic: Implements complex grading rules using logical operators (and, or) and nested conditions. Attendance Boost: Includes a specialized rule where students with good attendance can earn a higher grade (B) with a score of 65.
