# Knio Pages

The Knio project page is a [jekyll](https://jekyllrb.com/) project.

 - *Theme*: [minimal-mistakes-jekyll](https://mmistakes.github.io/minimal-mistakes/) 

# Setup
### Prerequisites
 1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) `>= 3.2.3`
 2. Install [bundler](https://bundler.io/) & [jekyll](https://jekyllrb.com/docs/installation/)

After installing Ruby, run the following command to install bundler and jekyll: 
 ```bash
 gem install bundler jekyll
 ```

# Run
To run the project locally, navigate to the project directory and run the following command:
```bash
bundle install
bundle exec jekyll serve
```

# Project Structure
```
 /root
   # Directories
   |-- _data        # Data files
   |-- _pages       # Pages
   |-- _posts       # Posts (News / Releases / etc.)
   |-- assets       # Assets (images, css, js, etc.)
   |-- build        # Build artifacts
   |-- release      # Release artifacts
   
   # Files
   |-- _config.yml  # Jekyll configuration
   |-- Gemfile      # Ruby dependencies
   |-- index.md     # Home page
   |-- README.md    # This README
```