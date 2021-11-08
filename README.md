# node-red-contrib-melcloud
node-red node for mitsubishi with melcloud API

Enter your credentials (email & password) from your Mitsubishi
melcloud account on https://app.melcloud.com/

First Node : melcloud-connect is provided in order to retrieve your
devices lists

![Alt text](melcloud-connect.png "Melcloud-connect")


Second Node : melcloud-device is provided in order to retrieve a
device informations (buildingid and deviceid are shown with
melcloud-connect)


![Alt text](melcloud-device.png "Melcloud-device")

All provided setting (switch on/off, temperature, fan speed, mode ...) will update your melcloud configuration 
