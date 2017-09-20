# Asciidots on docker

Run [asciidots][] in a docker container.

Run a program `test.dots` in the current directory:

    docker run -ti --rm -v $PWD:/data francois2/asciidots /data/test.dots

Run the samples from the original asciidots repository:

    docker run -ti --rm  francois2/asciidots asciidots/samples/hello_world.dots

[asciidots]: https://github.com/aaronduino/asciidots
