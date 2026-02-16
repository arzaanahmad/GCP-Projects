# Project: Resize Persistent Disk of a VM in Google Cloud

## Objective
To increase the size of a persistent disk attached to a Virtual Machine and expand the file system inside the VM.

## Services Used
- Google Compute Engine
- Persistent Disk
- Linux file system tools

## Why Disk Resize is Important
Disk resizing is needed when:
- Storage is running out
- Applications require more space
- Scaling storage without creating new VM

## Steps I Followed
1. Checked the current disk size in GCP Console.
2. Edited the disk configuration.
3. Increased the disk size.
4. Connected to the VM using SSH.
5. Verified disk using `lsblk` and `df -h`.
6. Resized the file system inside the VM.

## Commands Used
(See commands.txt file)

## Proof (Screenshots)
- original-disk-size.png → Initial disk size
- disk-size-updated.png → Updating disk size
- disk-resized-console.png → New size visible in console
- disk-check-terminal.png → Verified disk inside VM

## What I Learned
- Persistent disk size can be increased but not decreased.
- After resizing disk in console, file system must be expanded manually.
- Difference between disk size and file system size.
- How to verify storage using Linux commands.

## Next Steps
- Try resizing disk using gcloud CLI.
- Compare standard disk vs SSD disk.
