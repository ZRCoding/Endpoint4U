# Endpoint4U

Endpoint4U is a flexible, scalable ZombsRoyale.io asset endpoint created by Jamz.

# How to Use

### Main Endpoint

The URL of the API endpoint is
```
https://endpoint4u.projectagon.repl.co
```

### Features

- ``/model/body/`` - Generates a body model
    - **Required Parameters**
        - ``skin``, the internal name of the skin this model should use.
        Example: ``?skin=2000GameModel``
    - **Optional Parameters**
        - ``width``, the width that this model should be scaled to. 512 pixels if this parameter is not included. Maximum: 1024.
        Example: ``&width=256``
        - ``height``, the height that this model should be scaled to. 512 pixels if this parameter is not included. Maxiumum: 1024.
        Example ``&height=1024``
