# cardreadd
Use RFIdeas pcProx card reader with Growing Panes

cardreadd relies on the "pcProx Enroll Configuration Utility for Linux", which can be downloaded from https://www.rfideas.com/files/downloads/software/CmdpcProx.tar.gz
The archive should be extracted in this directory.

cardreadd also requires the Growing Panes config file located at /etc/video_wall_config.json or an alternative location specified with the environment variable VIDEO_WALL_CONFIG_FILE

I am using cardreadd in conjunction with a RDR-60W1AKU wall-mount keystroking card reader. If I were ordering hardware again I probably would have gotten one of the models that acts as a com port (like RDR-60W1AK0), which would then hopefully not require any binaries from RFIdeas.

