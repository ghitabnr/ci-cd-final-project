# CI/CD Tools and Practices Final Project Template
Project name: `ci-cd-final-project`
This project uses the IBM Skills Network counter microservice template for the Coursera Continuous Integration and Continuous Delivery (CI/CD) course.
## Pipeline
GitHub Actions checks out the source, installs dependencies, runs Flake8, and runs the Nose unit tests. The OpenShift pipeline runs cleanup, git-clone, linting, tests, image build, and deployment.
## Setup
```bash
bash bin/setup.sh
```
Open a new terminal to activate the Python environment.
## License and attribution
Licensed under the Apache License. See [LICENSE](LICENSE).
Original application template: Skills Network, © IBM Corporation 2023. All rights reserved.
