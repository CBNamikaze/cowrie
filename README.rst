Cowrie
######

Welcome to the Cowrie GitHub repository
*****************************************

This is the official repository for the Cowrie SSH and Telnet
Honeypot effort.

What is Cowrie
*****************************************

Cowrie is a medium to high interaction SSH and Telnet honeypot
designed to log brute force attacks and the shell interaction
performed by the attacker. In medium interaction mode (shell) it
emulates a UNIX system in Python, in high interaction mode (proxy)
it functions as an SSH and telnet proxy to observe attacker behavior
to another system.

`Cowrie <http://github.com/cowrie/cowrie/>`_ is maintained by Michel Oosterhof.

Documentation
****************************************

The Documentation can be found `here <https://cowrie.readthedocs.io/en/latest/index.html>`_.

##Commands
#To Create Venv
python3 -m venv cowrie-env

#To Activate Venv
source cowrie-env/bin/activate

#To Install Requirements
python -m pip install --upgrade -r requirements.txt

#To Start Cowrie
bin/cowrie start


#To Stop Cowrie
bin/cowrie Stop
