# install-scripts
__A bunch of bash scripts to install stuff in Ubuntu.__

## Scripts
  * `install-tailscale` - Installs tailscale to apt sources
  * `install-nvidia-cuda-repo` - Latest packaged versions of CUDA (network repo, update with apt).
  * `upgrade-old-release` - Makes `do-release-upgrade` work when your release is past EOL.

## Assumptions
  * Scripts run as a user who can `sudo` (without password for non-interactive mode), but not as root.
  
## Notice
  * I try to make these scripts version agnostic but distribution zealotous (#UbuntuGang)

## Contributing
  * If I screwed something up, please send a PR
