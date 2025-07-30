# jwahle.github.io

On Linux/Mac with Docker installed, you can run it locally with: 
```shell
docker run --volume "$PWD:/srv/jekyll" --publish 4000:4000 jekyll/jekyll jekyll serve
```

To update the `Gemfile.lock`, run
```shell
docker run --volume="$PWD:/srv/jekyll" -it jekyll/jekyll bundle update
```