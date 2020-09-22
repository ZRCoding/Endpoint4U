# Endpoint4U

Endpoint4U is a flexible, up to date and scalable ZombsRoyale.io asset endpoint created by Jamz.

# How to Use

### Main Endpoint

The URL of the API endpoint is
```
https://endpoint4u.projectagon.repl.co/
```

### Features

- ``/model/body/`` - Generates a body model<br/><br/>
    - **Required Parameters**
        - ``skin``, the internal name of the skin this model should use.
        Example: ``?skin=2000GameModel``<br/><br/>
    - **Optional Parameters**
        - ``width``, the width that this model should be scaled to. 512 pixels if this parameter is not included. Maximum: 1024.
        <br/>Example: ``&width=256``
        - ``height``, the height that this model should be scaled to. 512 pixels if this parameter is not included. Maxiumum: 1024.
        <br/>Example: ``&height=1024``
        - ``rotation``, the rotation value (in degrees) of this model. Rotates **counter-clockwise.**
        <br/>Example: ``&rotation=180``<br/><br/>
    - **Example Usage**<br/>
        - Created from ``https://endpoint4u.projectagon.repl.co/model/body?skin=AfroPink&width=256&height=256``<br/>
        ![image](https://endpoint4u.projectagon.repl.co/model/body?skin=AfroPink&width=256&height=256)
        
