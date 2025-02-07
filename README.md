# William E. Byrd's Blog

## Running website locally

On mac, install Ruby with homebrew: `brew install ruby`.

After installation, the quick shell commands I run on my mac (each terminal session) are:
- `export PATH="/opt/homebrew/opt/ruby/bin:$PATH"`
- `bundle install`
- `bundle exec jekyll serve`

The last command serves the website at `http://localhost:4000`.

## Adding a post

Add a `md` file in `_posts` directory in the format `YYYY-MM-DD-path.md`. The preambule in between `---` lines should contain `layout: post` and `title: XXX`.
