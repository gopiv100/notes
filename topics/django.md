# Overview

# Installation

Make sure that you have pip3 installed on Ubuntu. Create an isolated virtual environment(`my_env`) so that it is possible for multiple versions of django instances to co exist in case you are working on an older project with different version of django. Activate the created `my_env` and then install django version needed using pip.

```sudo apt-get install python3-pip
python -m venv my_env
source my_env/bin/activate

pip install "Django==3.0.*"
```
