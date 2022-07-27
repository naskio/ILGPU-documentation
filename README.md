# Contributing

## Development

### Running Locally

```shell
jekyll serve --config _config.yml,_config.development.yml
# or
jekyll serve --baseurl ""
jekyll serve --baseurl=""
```

## Production

The website will be built and deployed automatically by GitHub.


## Create links

```shell
# symbolic link
ln -s [SOURCE] [TARGET]
ln -s Docs/ _posts
ln -s excluded_folder/hello.md hello.md
# hard link
sudo gln -d ../Docs _posts
```
