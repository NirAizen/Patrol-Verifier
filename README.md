# Patrol-Verifier

Part of the Security Control Room in Meta is to verify the patrol points that the security guards scan with their phones.
The Points Checker project aims to streamline this process by providing a user-friendly graphical interface to compare scanned points with the expected list.
This PyQt-based application takes scanned Excel files and compares them against a source Excel file containing the expected points.

Methods Used:

PyQt5 GUI: Developed using the PyQt5 framework, the application offers an intuitive and responsive user interface for easy interaction.
Excel Data Comparison: The app reads and processes Excel files to extract patrol point data, then performs comparisons to identify any discrepancies.
Dynamic Theme Switching: Users can switch between light and dark themes for optimal visibility.
Missing Point Detection: The application identifies and displays missing patrol points, highlighting potential security concerns.
Interactive Output: Detailed comparison results can be copied to the clipboard, facilitating further analysis or reporting.
