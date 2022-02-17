# AI-for-cybersecurity
This repo contains the project developed for AI  for cybersecurity course 

The project's aim was to devise a heuristic to estimate the suspiciousness level of log patterns.

## Processing steps

Starting from raw data of login/logout attempts:

* Features elaboration
* Attempts series construction
  - For user
  - For source IP
* Heurist function calculation

For more details see docs/project presentation.pdf

## Run our code

1. Create a virtual environment
2. Install all requirements in requirements.txt
3. ipython kernel install --user --name=_your environment_
4. open the project via jupyter and select the new kernel "_your environment_"

### Example
1. python3.9 -m venv venv && source venv/bin/activate
3. pip install -r requirements.txt
4. ipython kernel install --user --name=venv

### Contacts
Drop an email to retrieve the masqueraded dataset to:
* [Carlo Leo]
* [Riccardo Gallo]

[Carlo Leo]: <mailto:carlo_leo97@outlook.it>
[Riccardo Gallo]: <mailto:rjknet99@icloud.com>
