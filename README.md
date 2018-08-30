# windowsiana
[![GoDoc](https://godoc.org/github.com/thinkovation/windowsiana?status.svg)](https://godoc.org/github.com/thinkovation/windowsiana)
[![Go Report Card](https://goreportcard.com/badge/github.com/thinkovation/windowsiana)](https://goreportcard.com/report/github.com/thinkovation/windowsiana)

A very simple package that helps when dealing with Windows timezones and mapping them to standard timezones.

I created this package to handle times that were sent back from a web service that were sent with details of the Windows timezone to which they were tied. In order to make the time usable in Go, I created this little package to allow me to convert an inbound Windows time into a propert time.

The list is also inspired by the Microsoft Graph API and as of 30th August 2018 compatible to all timezones listed by https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/api/outlookuser_supportedtimezones
