# windowsiana
A very simple package that helps when dealing with Windows timezones and mapping them to standard timezones

I created this package to handle times that were sent back from a web service that were sent with details of the Windows timezone to which they were tied. In order to make the time usable in Go, I created this little package to allow me to convert an inbound Windows time into a propert time.

See https://godoc.org/github.com/thinkovation/windowsiana for docs.
