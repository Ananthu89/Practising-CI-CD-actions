Scripts with Python (for the purpose of testing CI/CD actions) 

Notes: 

1. A continuous integration (CI) action has been added successfully. To complete all the tests successfully we need to add two files ('requirments.txt' and 'test_example.py'). The latter needs to have an "assert" statement. The 'requirments.txt' may not be as mandatory as the other one. 

2. For continuous deployment (CD), there needs to be (an output folder with) static files, which are files like HTML, CSS, JavaScript, or images that don’t change based on user interaction. I have created an output folder named "static_site" and added a very simple HTML file (as Python files are not sufficient for this purpose). 

3. Finally, following deployment, the HTML file content in the "static_site" folder gets published via Netlify (check https://app.netlify.com/teams/ananthu89/sites for details). By modifying the HTML file, automatically the published content also changes! 
