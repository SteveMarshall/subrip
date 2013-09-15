Extract subtitles from `VOB` files and use OCR to make a `.srt` of them.

Requirements
============

- Some Perl modules: `cpanm Image::Magick Web::Scraper`
- Some native softare: `brew install imagemagick dvdauthor dvdbackup netpbm tesseract --all-languages`

Todo
====

- Check for required executables using `which`?
- Package properly
- Automate more
- Move replacements to user config?
