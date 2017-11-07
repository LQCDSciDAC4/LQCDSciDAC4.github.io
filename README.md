# LQCDSciDAC4.github.io
Web pages for US Dept. of Energy ASCR/NP LQCD SciDAC-4 project

_____


Instructions for building a local version for testing:

MacOS: brew install ruby (this provides “gem”)

Linux: apt-get install ruby

gem install jekyll

gem install bundler

git clone git@github.com:LQCDSciDAC4/LQCDSciDAC4.github.io.git

cd hadspec

bundle install

cd docs

jekyll build

jekyll serve

then in your favourite web browser you can type:

http://127.0.0.1:4000

