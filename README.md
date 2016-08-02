# git-playground
play with git branching model and other stuff

* master: development trunk, MUST be always deployable
* feature-branch: fork from master, MUST NOT break build on merging back to master
* release-branch(vx.x): fork from master, deploy on staging then on production. Tag the final released production with verion number.
