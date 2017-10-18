This is the example repository for [this blog post](https://www.sohamkamani.com/blog/2017/09/13/how-to-build-a-web-application-in-golang/)

To run the server on your system:

1. Make sure you have [dep](https://github.com/golang/dep) installed
2. Run `dep ensure` to install dependencies
3. Run `go build` to create the binary (`blog_example__go_web_app`)
4. Run the binary : `./blog_example__go_web_app`

To run tests:

2. Run `dep ensure` to install dependencies
2. Run `go test ./...`