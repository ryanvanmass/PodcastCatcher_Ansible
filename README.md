# Chimeara Podman Hosts
## Role
This Server acts as a automatic Podcast and Video (Youtube) Downloader in addition to a CLoudC2 Server

## Services
* Podman
* NFS

### Podman Containers
(All build from Dockerfile)
* Youtube-Dl
* Upodder
* CloudC2

### NFS Shares
* Access to FileSync Share hosted by DeathStar

## Setup
### Server
Run Ansible Playbook and follow any prompts

### Container
Most of the containers have a `Setup.sh` File to run