[![](https://images.microbadger.com/badges/image/thawk/asciidoctor.svg)](https://microbadger.com/images/thawk/asciidoctor) [![](https://images.microbadger.com/badges/commit/thawk/asciidoctor.svg)](https://microbadger.com/images/thawk/asciidoctor) [![](https://images.microbadger.com/badges/version/thawk/asciidoctor.svg)](https://microbadger.com/images/thawk/asciidoctor)

Run asciidoctor in a container.

## Usage

```sh
$ docker run -it --rm -v $(pwd):/documents/ thawk/asciidoctor asciidoctor -r asciidoctor-diagram document.adoc
```

