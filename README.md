# pysimdjson

Python bindings for the [simdjson][] project, a SIMD-accelerated JSON parser.
If SIMD instructions are unavailable a fallback parser is used, making
pysimdjson safe to use anywhere.

> [!NOTE]
>
> This fork ships python 3.8 wheel files for Sublime Text 4 plugin ecosystem.

## 📝 Documentation

The latest documentation can be found at https://pysimdjson.tkte.ch.

If you've checked out the source code (for example to review a PR), you can
build the latest documentation by running `cd docs && make html`.

## 📈 Benchmarks

pysimdjson compares well against most libraries. The full benchmarks can be
found in its sister project [json_benchmark][].

[simdjson]: https://github.com/lemire/simdjson
[json_benchmark]: https://github.com/tktech/json_benchmark
