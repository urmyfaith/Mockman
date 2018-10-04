# <img alt="Mockman" width="150" height="150" src="http://orhcxc3kd.bkt.clouddn.com/256x256.png"/>

![](https://img.shields.io/github/repo-size/lancegin/mockman.svg)
![](https://img.shields.io/github/release/lancegin/mockman.svg)
![](https://img.shields.io/github/last-commit/lancegin/mockman.svg)

> `Mockman` is a powerful and convenient tool that helps you to manage and start mock servers locally.
> 
> With the app, you can easily configure the routes, request format and response of a mock server

## Screenshot

![Mockman](http://orhcxc3kd.bkt.clouddn.com/mockman.png)

## Usage

![Feature](http://orhcxc3kd.bkt.clouddn.com/mockman-preview.jpg)

1. Create your mock server - `click the add button`
2. Configure the `name`, `port` and `prefix` of your move server, make sure the port is not in use, or Mockman will give you a error notification.
3. Add some apis for your mock server.
4. Configure the `method`, `route`, `response code`, `latency`, `required request options` and `reponse data` of each api.
5. Start the server - `click the start button`.
6. After all, you can test your api locally.

> Where will your api data be stored?
> 
> Your data will be stored as a `sqlite file` absolutely on your local, the path will be different on different operation system. 
> 
> * `%APPDATA%`  for Windows
> * `$XDG_CONFIG_HOME or ~/.config` for Linux
> * `~/Library/Application Support` for macOS

## Todos

### Server

- [x] ipcMain && ipcRender communication
- [x] dababase support
- [x] create a new mock
- [x] update a mock
- [x] remove a mock
- [x] query a mock info
- [x] create an api
- [x] update an api
- [x] remove an api
- [x] query an api info
- [x] start an express server with a mock config
- [x] handle errors while starting the server

### Client

- [x] brand header dislay
- [x] mock sider display
- [x] mock-detail and api-list display
- [x] api-detail display
- [x] create a new mock
- [x] update a mock
- [x] remove a mock
- [x] query a mock info
- [x] create an api
- [x] update an api
- [x] remove an api
- [x] query an api info
- [x] request params check list
- [x] response k-v input group
- [x] response code editor
- [x] add blur event to jsonEditor
- [ ] group the apis with tag
- [ ] check the conflict of all mocks
- [ ] add a log panel to show the logs of an active mock server process
- [ ] add https support



## License

[![license](https://img.shields.io/github/license/lancegin/mockman.svg)]()

## Contribute

``` bash
# install native dependencies through `native.sh`
./native.sh

# serve with hot reload at localhost:9080
npm run dev 

# build mockman
npm run build

# run unit tests
npm test 

# lint all JS/Vue component files in `src/`
npm run lint 

```

---
