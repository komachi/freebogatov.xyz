# freebogatov.org

Support website about jailed russian mathematician and software developer Dmitry Bogatov.

## How to build and run

```bash
git clone https://github.com/komachi/freebogatov.org.git && cd freebogatov.org
bundle install
bundle exec jekyll serve
```

## How to build in [Termux](https://termux.com/)

```bash
apt install git make clang nodejs ruby ruby-dev libffi-dev libxml2-dev libxslt-dev pkg-config
git clone https://github.com/komachi/freebogatov.org.git && cd freebogatov.org
gem install bundle pkg-config
gem install nokogiri -- --use-system-libraries
bundle install
bundle exec jekyll serve
```
