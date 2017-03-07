# tech304.io

tech304 website

## Development

### Bare metal

```bash
gem install jekyll
jekyll serve --watch
```

### Docker

```bash
docker run -it --rm --label=jekyll --volume=$(pwd):/srv/jekyll \
  -p 127.0.0.1:4000:4000 jekyll/jekyll jekyll serve
```
