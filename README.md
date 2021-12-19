# Simple HTTP server

Writen on GO based on standard library and Google's distroless: <https://github.com/GoogleContainerTools/distroless>.

Build image:
**docker build -t http-go .**

Start container:
**docker run -it -p 80:80  http-go**
