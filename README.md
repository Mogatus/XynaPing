# XynaPing
An example API for Xyna Factory.

## Installation of Xyna
1. Get docker-compose-example file from https://github.com/Xyna-Factory/xyna-images/tree/main/dockerHub and save it as docker-compose.yaml
2. Execute docker-compose up -d from the folder with the compose file.
3. Log in with XYNA/XYNAPW and create a new user. URL: http://localhost:8000/modeller
4. Install Apps
    1. docker exec -it xyna-xyna-1 bash
    2. ./xynafactory.sh importapplication -filename /tmp/XynaBlackEdition/components/xint/RegExp.1.0.1.app
    3. ./xynafactory.sh importapplication -filename /tmp/XynaBlackEdition/components/xfmg/Json.1.3.1.app
    4. ./xynafactory.sh importapplication -filename /tmp/XynaBlackEdition/components/xfmg/OAS_Base.1.4.2.app
5. Reload GUI
6. Import XynaPing.yaml
