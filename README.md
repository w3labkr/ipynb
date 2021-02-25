# Jupiter Notebook

A collection of frequently used Jupiter notebook code.

## Directory Structure

```
o
`-- scrapper/
    `-- naver.com/
```

## scrapper

An easy-to-use web scraper on juypiter notebook.

**Installation**

```
(base) pip install selenium
(base) pip install chromedriver-autoinstaller
```

**Usage**

```python
params = {
    'section': 'qna', # kin, qna, ency
    'period': '1w', # 1w, 1m, 2002.01.01.%7C2020.12.09.
    'page': 1,
    'query': '여자친구+선물',
}
```

## License

Jupiter Notebook is licensed under the [MIT LICENSE](LICENSE)
