# Setup
1. Install VPN for PACE-ICE access. [Download instructions.](https://gatech.service-now.com/home#globalprotect-vpn-client)
2. Enable VPN everytime before logging into PACE.
3. Login to PACE and enter password.
`ssh <user_name>@login-ice.pace.gatech.edu`
4. Allocate compute using a `slurm` command. Sample command `srun --nodes=1 --ntasks=1 --cpus-per-task=7 --gres=gpu:1 --time=08:00:00 --pty bash`
5. Install miniconda `wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh`
6. Follow LeRobot install instructions.

### Resources
[Using Slurm on ICE.](https://gatech.service-now.com/home?id=kb_article_view&sysparm_article=KB0042096)

# Datasets to Evaluate On
- Robomimic
- Push-T
- Multimodal Block Pushing
- Franka Kitchen