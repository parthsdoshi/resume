# Parth's Resume
To build the resume, you need to have LaTeX installed on your system.

For MacOS:
```bash
brew install --cask mactex-no-gui
brew install just
```
Note: the mactex install can take forever if it chooses a bad CTAN mirror. Feel free to install it manually instead of homebrew if you want it to be faster.

Then run:
```bash
just build
```
to output `resume.pdf` to `out/`.
