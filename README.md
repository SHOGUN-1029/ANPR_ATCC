This project implements an intelligent traffic management system utilizing Automatic Number Plate Recognition (ANPR) and Automatic Traffic Classification and Control (ATCC). By leveraging Deep Learning and Object Detection techniques, the system automates traffic monitoring and control in smart city environments.

Key Features
Automatic Number Plate Recognition (ANPR)
Automatic Traffic Classification and Control (ATCC)
Data interpolation for accurate tracking
Visualization capabilities

Results
you can find the result video at this location : https://drive.google.com/file/d/1YkynwRblC3HgEqTt5CtDrCDZkizdOZ_r/view?usp=drive_link


Workflow
Execute main.py to perform initial vehicle detection and generate CSV file in results/ directory
Run add_missing_data.py to perform data interpolation and generate enhanced CSV file in Interpolated_results/ directory
Run visualize.py to create visualization video using interpolated data, saved in output_videos/ directory
