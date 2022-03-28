# Go package redirector

Do you want custom Go import paths like this?

```go
import "go.yourdomain.com/yourpackage"
```

If yes, **follow these simple steps**:

1. [Use this template](https://github.com/haveyoudebuggedit/go-custom-import-paths/generate) and create a repository in your own organization **named `go.yourdomain.com`**.
2. Customize the [packages.json](packages.json) file.
3. Set up a DNS record: `go.yourdomain.com. IN CNAME yourgithuborg.github.io.`

How does it work? [Read the blog post here.](https://debugged.it/blog/custom-go-import-paths)

