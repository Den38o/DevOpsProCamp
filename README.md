# DevOpsProCamp
DevOpsProCamp test task description:

As a DevOps engineer you need to collect metrics about your linux server. Unfortunately you cannot use any monitoring solution and need to implement something by your own.

    Implement a script which prints basic information about your OS to console.

    Package your service into Docker container (Optional).

    Write README.md file with documentation about your script/container.

    Publish the project to GitHub.

    Send us a link to GitHub repository with your project.

## Getting Started

Clone project from git to your local machine:

```
git clone https://github.com/Den38o/DevOpsProCamp.git
```

### Prerequisites

This script is tested under the following system's setup:
Debian 8.2, Python 3.4.2, psutil 5.4.5

### Installing

install Python:
```
sudo apt-get update
sudo apt-get install python3
```

Install psutil python library:
```
sudo apt-get install gcc python-dev python-pip
pip install psutil
```
## Running the tests

run script:
```
./metric cpu
./metric mem
```
