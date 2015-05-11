Python API and command-line interface for working with Sonatype Nexus
=====================================================================

How to run commands locally:
PYTHONPATH=$PWD scripts/{artifact,repo}

How to run tests locally:

1. Install pycharm >=3.4.1
1. Install virtualbox and vagrant
1. Tools -> Vagrant -> Up
1. Settings -> Interpretters -> add -> remote -> vagrant
1. Run -> Edit Configurations -> add variables REPOSITORY_PASSWORD (nexus admin password) and REPOSITORY_URL.
   The nexus instance has to be professional for some tests.
1. Shift F10