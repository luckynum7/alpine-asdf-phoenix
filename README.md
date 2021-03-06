# docker-asdf-elixir

Docker image for CI, build w/ `asdf, erlang, elixir` [timefairy/docker-asdf-elixir](https://hub.docker.com/r/timefairy/docker-asdf-elixir/)


## Supported tags and respective `Dockerfile` links

-   `latest` [Dockerfile](https://github.com/luckynum7/docker-asdf-elixir/blob/master/Dockerfile)
-   `1.4.2_erl19.3` [Dockerfile](https://github.com/luckynum7/docker-asdf-elixir/blob/1.4.2_erl19.3/Dockerfile)
-   `1.4.2` [Dockerfile](https://github.com/luckynum7/docker-asdf-elixir/blob/1.4.2/Dockerfile)
-   `1.3.4` [Dockerfile](https://github.com/luckynum7/docker-asdf-elixir/blob/1.3.4/Dockerfile)


## Try it

```bash
docker run -ti --rm timefairy/docker-asdf-elixir:latest
```


## References

1.  <https://github.com/asdf-vm/asdf>
2.  <https://github.com/asdf-vm/asdf-erlang>
3.  <https://github.com/asdf-vm/asdf-elixir>


### About debian image

1.  <https://hub.docker.com/r/philcryer/min-wheezy/>
2.  <https://github.com/MonsantoCo/docker-min-jessie>
3.  <https://hub.docker.com/_/debian/> - Locales


### `asdf-erlang` dependencies

1.  <https://github.com/asdf-vm/asdf-erlang>


### asdf install new version in CI

1.  <https://github.com/parroty/circle_sample/blob/master/circle.yml>

```yaml
# - erlang_version=$(awk '/erlang/ { print $2 }' .tool-versions) && asdf install erlang ${erlang_version}
# - elixir_version=$(awk '/elixir/ { print $2 }' .tool-versions) && asdf install elixir ${elixir_version}
```
