# repo-configs
This repository contains `repo.cfg` files and files with CVMFS configuration for the EESSI repositories. Together, these allow the `eessi-bot-software-layer` bot to mount the EESSI repositories in our build containers, in order to be able to build software for EESSI.

To use these repository configurations, you typically point the `repos_cfg_dir` configuration item of your `eessi-bot-software-layer` instance to the `repos/production` or `repos/dev` directories within this repository, depending on whether you want to make the `software.eessi.io` or `dev.eessi.io` configuration available in your builds.
