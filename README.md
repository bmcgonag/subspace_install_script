# Subspace / Wireguard BASH Installation Script

This script is made to install wireguard, docker, and the subspace docker image / container onto a Ubuntu 18.04 or later server.

You may use and modify this script freely, and it is provided AS IS and without warranty or guarantee.  Use at your own risk. 

## How to use it.

1. Clone the repository to your server, or if you clone it to your own machine, move the subspace_install.sh file to your server.
2. Check the script to your own satisfaction.
3. Run the script using the command

`sh ./subspace_install.sh`

This would be run as root.  If you are not logged in as root, you may need to modify the sommands in the script by adding 'sudo' before each command.

The script will run, and will only stop once to request your server's FQDN.

Enter it as either:

domain.com

or 

subdomain.domain.com


### Example

my FQDN would be vpn.opensourceisawesome.com

4. Once the script completes, you should be able to browse to your domain / subdomain and create your initial administrative account on your new subspace installation.

