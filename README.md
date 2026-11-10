# Hi, I'm Aryan

I'm a Lead AI Engineer based in India.

Open source is my hobby. In my spare time I find and fix bugs in libraries I use or like, mostly Python (machine learning, data and packaging tools), with some Java and C++.

## Some merged fixes

- **[tesseract](https://github.com/tesseract-ocr/tesseract)**: file names containing `&` no longer produce invalid ALTO and PAGE XML ([#4652](https://github.com/tesseract-ocr/tesseract/pull/4652)), and `min_characters_to_try` now reaches the separate orientation and script detection engine ([#4651](https://github.com/tesseract-ocr/tesseract/pull/4651)).
- **[docling](https://github.com/docling-project/docling)**: JATS conversion keeps table footnotes instead of dropping them ([#4818](https://github.com/docling-project/docling/pull/4818)).
- **[pipx](https://github.com/pypa/pipx)**: `--include-resources-from` accepts dependencies that only ship shell completions ([#2157](https://github.com/pypa/pipx/pull/2157)).
- **[statsmodels](https://github.com/statsmodels/statsmodels)**: predicting from a pandas Series works for single-predictor models with extra fitted parameters ([#10590](https://github.com/statsmodels/statsmodels/pull/10590)).
- **[xarray](https://github.com/pydata/xarray)**: `to_unstacked_dataset()` works after selecting features from a stacked array ([#11808](https://github.com/pydata/xarray/pull/11808)).
- **[darts](https://github.com/unit8co/darts)**: `MIDAS.fit_transform()` handles short multivariate and sampled series ([#3304](https://github.com/unit8co/darts/pull/3304)).
- **[feast](https://github.com/feast-dev/feast)**: Dask historical retrieval no longer confuses a source's created timestamp with a request column of the same name ([#7071](https://github.com/feast-dev/feast/pull/7071)).
- **[msgspec](https://github.com/msgspec/msgspec)**: `Encoder.encode_lines` releases its iterator reference on success and error paths ([#1284](https://github.com/msgspec/msgspec/pull/1284)).
- **Apache**: fixes in [commons-lang](https://github.com/apache/commons-lang/pull/1824), [commons-io](https://github.com/apache/commons-io/pull/887), [commons-codec](https://github.com/apache/commons-codec/pull/448), [commons-numbers](https://github.com/apache/commons-numbers/pull/223) and [POI](https://github.com/apache/poi/pull/1433).

The full list of merged pull requests, grouped by area, is in [oss-contributions](https://github.com/AryanRG/oss-contributions).

## My own projects

- [relay-shelf](https://github.com/AryanRG/relay-shelf): a lightweight native macOS file shelf for collecting files, pasting paths and previewing documents.

## Contact

[LinkedIn](https://www.linkedin.com/in/aryan-ganjoo/)
