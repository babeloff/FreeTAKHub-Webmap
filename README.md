# Web Map
Repository for the FreeTAK_Hub_Webmap
![image](https://user-images.githubusercontent.com/60719165/143499968-c8d4c3cc-3892-4a50-b285-2612ef540fd7.png)

See docs [here](https://freetakteam.github.io/FreeTAKServer-User-Docs/FreeTAKHub/WebMap/Installation/)

## Contents

### `freetakhub_config.json`

Deprecated.

This contains a flow for setting the global context variables.
Using global context variables is not guaranteed to be installed before they are used.
Since v3.1 NodeRED recommends using global environment variables instead.

### `freetakhub_webmap_v5.json`

Updates to use global environment variables.
Updates to use TAK nodes.


### `freetakhub_webmap.json`

Deprecated flow.

### `README.md`

This file.

### `WebMap.json`

Deprecated flow.

## Global Environment Variables

When using these flows there are a number of global environment variables which are expected:

Here are the names of those global environment variables and some sample values.

```
 "FTH_FTS_URL": "127.0.0.1"
 "FTH_FTS_TCP_Port": "8087"
 "FTH_FTS_API_Port": "19023"
 "FTH_FTS_API_Auth": "token"
```

This flow makes heavy use of worldmap.

* https://flows.nodered.org/node/node-red-contrib-web-worldmap
* https://github.com/dceejay/RedMap


## Issues

* https://github.com/dceejay/RedMap/issues/293
* https://github.com/dceejay/RedMap/issues/292

