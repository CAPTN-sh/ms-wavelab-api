# MS Wavelab API

You can find the full documentation of the MS Wavelab API here:

https://captn-sh.github.io/ms-wavelab-api/

Initial suggestion for MQTT topics

```
ms-wavelab/

    guidance/
        ...

    navigation/
        xsens/                      # ...
            ...
        anschuetz/
            synapsis/               # ADDIX Multicast Box, Wavelab
            ...
        addix/
            ais/                    # ADDIX AIS, Nordhafen
            radio/
            ...
        ahoyrtc/
            mediaengine/
            ahoyonboard/
                google-pixel-jp/
            ...
        boening/
            AHD-DPS02/              # Navigation Signal Lights Control Monitoring
            ...
        torqeedo/
            ...
            
    control/
        request/
            ...
        command/
            ...
```