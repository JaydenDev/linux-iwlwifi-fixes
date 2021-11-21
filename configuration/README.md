# To apply these fixes
```
git clone https://github.com/JaydenDev/linux-iwlwifi-fixes
``` 
\
```
cd linux-iwlwifi-fixes/configuration
``` 
\
```
sudo cp -r * /etc/modprobe.d/
``` 
\
```
sudo modprobe -r iwlmvm && sudo modprobe -r iwlwifi && sudo modprobe iwlwifi
```
