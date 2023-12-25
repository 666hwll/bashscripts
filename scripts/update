#! /bin/bash
echo -e  """\033[0;31m
------------------------------
|                            |
| Packages are being updated.|
|                            |
------------------------------
"""
sudo apt update && sudo apt upgrade -y
sudo apt-get update && sudo apt-get upgrade -y
echo -e """\033[0;32m
------------------------------
|                            |
| Packages have been updated.|
|                            |
------------------------------
"""
sudo apt autoremove -y
echo -e  """ \033[0;34m
----------------------------------------
|                                      |
| Unused dependecies have been removed.|
|                                      |
----------------------------------------\033[0;0m
"""
