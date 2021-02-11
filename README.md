## Installation

You will need *wget* (a standard Linux command to download files).

In macOS you can install [Homebrew](https://brew.sh) and type command ‘brew install wget‘

### Download the scripts from github

```
git clone https://github.com/jarfo/wikitext.git
cd wikitext
```

Then, the required python packages can be installed with pip3:

```
pip3 install -r requirements.txt
```

And you can download and preprocess de wikipedia pages with

```
./prepare_wiki.sh LL
```

where *LL* is the wikipedia language code (e.g. en, ca, es, bh, fr, ...)
