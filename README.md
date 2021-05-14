```
 _               _              _    ____  
| |    ___   ___| | _____ _ __ / \  |  _ \ 
| |   / _ \ / __| |/ / _ \ '__/ _ \ | |_) |
| |__| (_) | (__|   <  __/ | / ___ \|  _ < 
|_____\___/ \___|_|\_\___|_|/_/   \_\_| \_\
                                           
```
# Locker AR

### Project Description
- LockerAR is a project to combine AR with Locker system.

### Development Run Steps
Build up the environment.
```
cd web-AR/
pip install -r requirements.txt
```

Run backend server.
```
python -m server
```

GET /camera : open the camera.

If get the [open camera issue like this](https://github.com/jeromeetienne/AR.js/issues/463),
please using `ngrok` to provide a `https` site.


### Reference
- We will implement this project with [AR.js](https://github.com/AR-js-org/AR.js)
