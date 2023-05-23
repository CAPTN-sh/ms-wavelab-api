# ms-wavelab-api

https://captn-sh.github.io/ms-wavelab-api/

Initial suggestion for MQTT topics

```
wavelab/

    guidance/
        ...

    navigation/
        xsens/                      # ...
            ...
        anschuetz/
          synapsis/                 # ADDIX Multicast Box, Wavelab
                  ...
        addix/
            ais/                    # ADDIX AIS, Nordhafen
                raw/
                    ...
                json/
                    ...
            lte/
                ...
        ahoyrtc/
            AhoyOnBoard-01/
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