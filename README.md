# ioit-uniovi-docker-nodered
IoT Node-RED Docker Service Uniovi PoC

## Securize node-red
To securize node-red we must create passwords compatible with node-RED and we must to the node-RED Admin command line. for more details visit this link [node-RED Admin CLI](https://nodered.org/docs/user-guide/node-red-admin). To install we must execute this command:
 
```shell
npm install -g --unsafe-perm node-red-admin
```

No execute this command to create a new node-RED password compatible:
```shell
node-red-admin hash-pw
```