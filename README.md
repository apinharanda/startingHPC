# startingHPC

Some introductory notes about using the HPC cluster to run jobs. The instructions and examples specifically mention the CU HPC clusters, but they are applicable to any HPC cluster that uses the Slurm queuing system.

To start
1) check the resources below

https://rabernat.github.io/research_computing/introduction-to-the-habanero-hpc-cluster.html

Starts with log in, and then it mentions conda installations
Note, that I actually prefer to use conda like it is detailed Install_base_programs log.
If you load it as a module from the HPC all the conda modules will be in $HOME and so you will eventually run out of space. Also you cannot control the conda version you are using.
You will want to create a dir in the scratch space.

This is a longer version for Terremoto and Ginsburg
https://confluence.columbia.edu/confluence/display/rcs/Terremoto+HPC+Cluster+User+Documentation
https://confluence.columbia.edu/confluence/display/rcs/Ginsburg+HPC+Cluster+User+Documentation

To write a script in the cluster directly you can use vi, vim, etc
https://www.washington.edu/computing/unix/vi.html

When a job is submitted to the HPC, you can see its progress by:
squeue -u [UNI]

and you can cancel it by:
scancel [job number]

2) follow the instructions in the log file Install_base_programs.log to start working on the HPC

3) To add alias to your bashrc check the log add_alias_bashrc.log


