# Search Engine in Rust

[origin repo][https://github.com/tsoding/seroost]

Date: 12.06.2023
__References:__
- tf-idf: [https://en.wikipedia.org/wiki/Tf%E2%80%93idf]
- [https://github.com/BSVino/docs.gl]

Date: 25.06.2023
__References:__
- Stemming: [https://en.wikipedia.org/wiki/Stemming]
- Lemmatisation: [https://en.wikipedia.org/wiki/Lemmatisation]
- Snowball Programming Language: [https://snowballstem.org/]
- elasticsearch docs: [https://www.elastic.co/guide/en/elasticsearch/reference/current/stemming.html]

Date: 06.07.2023
__References:__
- PDF library: [https://poppler.freedesktop.org]

> JSON

```bash
js . index.json > index-pretty.json
```

> Snowball Stemming

```bash
git clone --depth=1 https://github.com/snowballstem/snowball.git
cd snowball && make
find -type f -executable
./snowball ./algorithms/english.sbl -o <output_file> -rust
cd rust && cargo build --release
```
