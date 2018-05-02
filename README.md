# traj-restapi
RestAPI for trajectory information.

### Install

You will need to have Python with [Virtualenv](https://virtualenv.pypa.io/en/stable/installation/) and [Git](https://git-scm.com/) installed on your machine.

I would recommend using Python 3, but Python 2 should work just fine.

First clone the repo somewhere on your disk.

`cd /path/to/my/workspace/`

`git clone https://github.com/Stuartlab-UCSC/traj-restapi`

`cd traj-restapi`

Create a virtual environment, fire it up, and install the requirments.

``virtualenv -p `which python3` venv``

`source venv/bin/activate`

`pip install -r requirements.txt`

Now you're ready to put the app in development mode and start it up.

`python setup.py develop`

`python traj_restapi/app.py`