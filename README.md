# tweetpy
Python package which to access the Tweet data without API

## Installation

The easiest way to install the latest version from PyPI is by using pip:
```
pip install tweetpy
```

## Usage

Download it by clicking the green download button here on Github. You only need to parse argument specific Twitter keyword.
```python
>>> from tweetpy.tweet import Tweet
>>> tweet = Tweet(1567531687130632199)
```
## Documentation

| ATTRIBUTE      | DESCRIPTION	 | VALUE      | EXAMPLE |
| ----------- | ----------- | ----------- | ----------- |
| `text` | get tweet text | String   | "Welcome to the home" |
| `conversation_count` | get conversation tweets count | Integer | 0 |
| `lang` | get tweet language code | String   | "en" |
| `favorite_count` | get likes count | Integer | 195 |
| `created_at` | get when the tweet created | datetime.datetime | datetime.datetime(2018, 8, 3, 2, 22, 56) |
| `id` | get tweet id | Integer  | 1025205344660856838 |
| `id_str` | get tweet id as string | String   | '1025205344660856838' |
| `possibly_sensitive` | is tweet has sensitive content | Boolean | False |
<!--
python  -m venv venv
source venv/bin/activate
pip install wheel setuptools twine
python setup.py sdist bdist_wheel
python -m twine upload dist/*
-->
