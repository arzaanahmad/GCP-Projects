# Project: Changing the Machine Type of a VM in Google Cloud

## Objective
To change the machine type of an existing Virtual Machine in Google Cloud.

## Services Used
- Google Compute Engine
- Virtual Machine Instances

## Why Machine Type Change is Important
Machine type determines:
- CPU power
- RAM capacity
- Performance
- Cost

## Steps I Followed
1. Identified the current machine type.
2. Stopped the VM (required before changing type).
3. Edited the VM configuration.
4. Changed machine type.
5. Restarted the VM.
6. Verified the new machine type.

## Proof (Screenshots)
- original-machine-type.png → VM before change
- vm-stopped.png → VM stopped
- machine-type-changed.png → Machine type updated
- vm-running-new-type.png → VM running with new configuration

## What I Learned
- A VM must be stopped before changing machine type.
- Machine type directly affects performance and cost.
- Scaling vertically (changing machine type) is different from horizontal scaling.
- Compare cost difference between machine types.
- Try changing machine type using Cloud Shell.
