# windowsiana

[![GoDoc](https://godoc.org/github.com/thinkovation/windowsiana?status.svg)](https://godoc.org/github.com/thinkovation/windowsiana)
[![Go Report Card](https://goreportcard.com/badge/github.com/thinkovation/windowsiana)](https://goreportcard.com/report/github.com/thinkovation/windowsiana)

A very simple package that helps when dealing with Windows timezones and mapping them to standard timezones.

I created this package to handle times that were sent back from a web service that were sent with details of the Windows timezone to which they were tied. In order to make the time usable in Go, I created this little package to allow me to convert an inbound Windows time into a propert time.

The list is also inspired by the [Microsoft Graph API](https://docs.microsoft.com/en-us/graph/overview) and as of 21st of May 2019 is compatible to all [outlookUser supportedTimeZones](https://docs.microsoft.com/en-us/graph/api/outlookuser-supportedtimezones)

## Technical prerequisites to develop/build

The program is as of 07/2021 developed with Visual Studio Code and several plugins. For enhanced compatibility and easier upgrading, golang is not installed locally anymore, but instead used via a docker container. Therefore the following may be installed on the development machine to develop without a local golang installation:

1. [Docker Engine](https://docs.docker.com/install)
1. [Visual Studio Code](https://code.visualstudio.com/) with the following plugins:
    * [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)
    * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
    * [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
    * [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)

The docker container used always uses the latest version of [golang](https://golang.org/dl/).
