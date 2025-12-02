# img-firefly

upload images to picbed like typora + picgo does.

two way to use: 

1. storage AccessKey locally.
2. (recommended) STS implementation, this plugin doesn't storage any KEY, use STS backend like picgo does.

## usage

require picgo installed.

linux: install picgo via `npm install -g picgo`

or self implement a picgo like backend, configure the backend address and request params in `config.json`.