# Port-Scanner

Port-Scanner is a simple python script I wrote to scan the ports either on my localhost or a remote host by making a call out to the remote host and returning what ports are open.

## Description

This is a simple program that ask the user to input a website host or hostname and provides output to the user on what ports are open on that host. The program is a static command line program that shows the user in a visual fashion what ports are open. 
## Getting Started

### Dependencies

* email.policy, socket, subprocess, sys, pyfiglet, datetime

### Installing

* No real install needed, just make sure you have the required modules.
```
pip install pyfiglet
```

### Executing program

* Run the program like any other common python script.
```
python scan.py
```

## Help
Common problems or issues are that you are not using an authorized user and need to switch to root.
```
sudo python scan.py
```

## Authors

Contributors names and contact info

Christopher Hyatt (me)
* [@codeslacker1155](https://github.com/codeslacker1155)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration taken from using the 'nmap' port scanning tool. 
