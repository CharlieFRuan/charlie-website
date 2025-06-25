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

Note we need to install hugo version 0.123.3. After installing it, do `brew pin hugo` to prevent updating.

Steps needed before to get hugo 0.123.3

```bash
brew unlink hugo
url -L https://github.com/gohugoio/hugo/releases/download/v0.123.3/hugo_extended_0.123.3_darwin-universal.tar.gz -o hugo_0.123.3.tar.gz
tar -xzf hugo_0.123.3.tar.gz
sudo mv hugo /usr/local/bin/hugo-0.123.3
sudo ln -sf /usr/local/bin/hugo-0.123.3 /usr/local/bin/hugo
hugo version
rm hugo_0.123.3.tar.gz LICENSE README.md
```
