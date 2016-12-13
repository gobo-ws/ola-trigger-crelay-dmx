**OLA Trigger config to control relays with DMX (ArtNet, sACN or via DMX input)**

OLA trigger configuration for controlling relays using crelay.

**Requirements**  

* OLA https://www.openlighting.org/ola/
* curl https://curl.haxx.se/
* crelay https://github.com/ondrej1024/crelay/
* one or more relays supported by crelay

**Installation**
  
* Download the [crelay.conf] (crelay.conf) file and edit the configuration section.

[OLA trigger documentation] (https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage**

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger crelay.conf`
