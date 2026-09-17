# Contributing to 0T-LeadRadar

Thank you for your interest in contributing to **0THack1A**!

## Bug Reporting
When opening an issue for a bug, please ensure you include:
1. The build version of the program (visible in the Information window from the `?` menu).
2. Exact steps to reproduce the problem.
3. If applicable, the session Log extract (`Menu -> Log -> Open log file`), removing any sensitive data of the analyzed companies.

## Development
The project is developed in **Python** and the user interface is designed to be Portable. 
* Ensure that any modification does not compromise the logic of the encrypted database (SQLCipher).
* **Do not introduce dependencies** that force a complex installation or break the self-containment of the program folder.
* When modifying the enrichment (scraping), remember to keep active the validation of the `robots.txt` file for each domain for the legal compliance of the software.

## Pull Requests
1. Fork the repository and create a branch for your feature (`git checkout -b feature/new-feature`).
2. Write clean and commented code where necessary.
3. Ensure that the final compiled executable can still correctly recognize the relative path of the `dati/` folder.
4. Open a Pull Request describing the changes made.
