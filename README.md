# 26F-3630
Website for CS 3630 taught in Fall 2026 by Frank Dellaert 

https://dellaert.github.io/26F-3630/

## Development Environment Setup

This website is built using Jekyll. To set up a local development environment, you will need to install a specific version of Ruby and some dependencies. The recommended way to do this on macOS is to use `rbenv`.

### 1. Install rbenv

If you don't have `rbenv` installed, you can install it using Homebrew:

```bash
brew install rbenv
```

After installing, you need to initialize `rbenv`. Run the following command and follow the instructions:

```bash
rbenv init
```

This will typically involve adding a line to your `~/.zshrc` or `~/.bash_profile` file and restarting your shell.

### 2. Install Ruby

Once `rbenv` is set up, you can install the correct version of Ruby:

```bash
rbenv install 3.2.2
rbenv global 3.2.2
```

You can verify that the correct version of Ruby is active with `ruby -v`.

### 3. Install Jekyll and Bundler

Next, install the necessary gems, `jekyll` and `bundler`:

```bash
gem install jekyll bundler
```

### 4. Run the Jekyll Server

Finally, you can navigate to the project directory and run the Jekyll server:

```bash
cd /Users/dellaert/git/26F-3630
jekyll serve
```

You should now be able to view the website at `http://localhost:4000`.