To deploy locally, run:

```bash
hugo server --disableFastRender
```

This may require the following steps on Mac:

```bash
brew install hugo
brew install go
hugo mod clean
hugo mod get -u ./...
hugo mod tidy
```
