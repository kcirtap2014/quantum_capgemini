# quantum_capgemini

## Installation

Go to path
`bash
cd /path/to/quantum_capgemini`

Create a virtual environment (you may skip this step if mds_env already exists in your directory)
`bash
virtualenv -p python3 q_env`

Activate virtualenv
`bash
. q_env/bin/activate`

Install requirements
`bash
pip install -r requirements.txt`

Adding virtualenv to jupyter notebook
Install jupyter
`bash
(q-env)$ pip install jupyter
`
Add kernel to jupyter
`bash
(q-env)$ ipython kernel install --name q-env --user
`