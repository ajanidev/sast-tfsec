This repository runs SAST test using tfsec. Before that, it runs the lint.py file to check if my another.tf file contains all the necessary variables and outputs the corresponding error if something is missing. 

In the same way, it exits code 0 if everything looks good and outputs "All checks are passed".