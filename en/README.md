# Minimal Gitbook Test

This repo contains a test book for testing plugins and themes that I plan to use with dronecode docs sites. E.g. 
* [PX4 Dev Guide](https://dev.px4.io/)
* [PX4 User Guide](https://docs.px4.io/)
* [QGC Dev Guide](https://dev.qgroundcontrol.com/)
* [QGC User Guide](https://docs.qgroundcontrol.com/)

The guide uses the [Gitbook](https://www.gitbook.com/about) toolchain. 

- Pages are written in separate files using markdown (the same syntax used by Github wiki). 
- The *structure* of the book is defined in a file named **SUMMARY.md**.
- This is a [multilingual](https://toolchain.gitbook.com/languages.html) book, 
  so there is a **LANGS.md** file in the root directory defining what languages are supported. 
  Pages for each language are stored in the folder named for the associated language code (e.g. "zh" for Chinese, "en" for English). 
- A file named **book.json** defines any dependencies of the build.
- A web hook is used to track whenever files are merged into the master branch on this repository, causing the book to rebuild.
- There is a [handy book editor](https://gitbookio.gitbooks.io/documentation/content/editor/index.html) you may find useful.

Everything you need to install and build Gitbook locally is explained in its [toolchain documentation](https://toolchain.gitbook.com/).
