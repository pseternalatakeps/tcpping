# TCP-PING
A simple python pinger developed to check specific TCP ports on a service or server.

# Installation
Ensure you have the default requirements.
```
sudo apt install git -y
sudo apt install python3 -y
sudo apt install python -y
sudo apt install pip -y
```
Download this repository via the following commnand.
```
git clone https://github.com/pseternalatakeps/tcpping.git
```
Update all databases and packages.
```
sudo apt update
```

# Usage
Once all the files are installed, go ahead and run the following command to ensure no problems occur.
```
chmod 777 *
```
Now, simply run this command to check a server's TCP port.
```
python3 tcpping.py <ipaddress> <port>
```

# Example
Here's an example of how to use this script.
```
python3 tcpping.py 1.1.1.1 443
```

# Credits
**Developer:** `Eternal Atake`<br>
**Creator:** `Eternal Atake`

