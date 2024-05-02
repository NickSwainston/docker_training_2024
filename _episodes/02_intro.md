---
title: "Introduction"
teaching: 5
exercises: 0
questions:
 - Where did this info come from?
 - Where can I learn more?
objectives:
 - Introduce the material
keypoints:
 - There are several places I can go to learn more
---

All of this info will stay on this website forever and it is all in a [GitHub repo](https://github.com/NickSwainston/docker_training_2024) if you spot mistakes and would like to fix them.

# Other lessons
This lesson is adapted from previous [ADACS workshops](https://adacs.org.au/adacs-training-vision/workshops/) which may contain other useful lessons:

- [2022B HPC training](https://adacs-australia.github.io/KLuken_HPC_training_2022B/)
- [ADACS Coding Best Practices](https://adacs-australia.github.io/2023-03-20-Coding-Best-Practices-Workshop/)

# Examples in other repositories
If you would like some examples of how docker containers are made, here are some examples I know of for pulsar software:

- [Presto and psrchive](https://github.com/CIRA-Pulsars-and-Transients-Group/psrchive_docker) two docker files made by the CIRA pulsar group for presto and psrchive
- [meerpipe](https://github.com/OZGrav/meerpipe) a [Dockerfile](https://github.com/OZGrav/meerpipe/blob/main/Dockerfile) I made to install pulsar software and then some of my python scripts on top and a [GitHub Action](https://github.com/OZGrav/meerpipe/blob/main/.github/workflows/docker_build_push.yml) to automatically build it when i push to the repo.
