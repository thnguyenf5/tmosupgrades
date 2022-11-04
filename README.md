# tmosupgrades
# day2ops-upgrades

This is meant to be part of a series of scripts to assist with Day 2 operations of the F5 ecosystem.

We'll be tackling items that will greatly streaming the time-consuming tasks within the operational responsibilites of F5 support teams.

This task was inspired by sebbycorp - https://github.com/sebbycorp/ansible-f5-upload-install-os

Some notable changes:
- Added a task to create a UCS archive file and download it off-box
- Modified some of the variable names to align with my other playbooks
- Modified server_port to 443 since my deployments were not in AWS

Notes:
- Please see https://clouddocs.f5.com/products/orchestration/ansible/devel/ for more information abour F5's ansible modules collection


