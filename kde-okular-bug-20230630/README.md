  # KDE Okular Annotions file size exploding bug

## Sample 1

* [original.pdf](https://github.com/jmbreuer/heap/raw/main/kde-okular-bug-20230630/original.pdf) the base/starting file
* [minimal-annotations.pdf](https://github.com/jmbreuer/heap/raw/main/kde-okular-bug-20230630/minimal-annotations.pdf) is `original.pdf` "Save as..." from Okular, adding some very few test annotations right on the first page
* [a-few-annotations.pdf](https://github.com/jmbreuer/heap/raw/main/kde-okular-bug-20230630/a-few-annotations.pdf) after adding a couple annotations on PDF page 7/document page number 3, based on `minimal-annotations.pdf` and removing its test annotations
* [a-few-resized-annotation-fonts.pdf.zstd](https://github.com/jmbreuer/heap/raw/main/kde-okular-bug-20230630/a-few-resized-annotation-fonts.pdf.zstd) [Zstandard](https://facebook.github.io/zstd/) compressed sample after adding a couple annotations, also on PDF page 7/document page number 3, also based directly on `minimal-annotations.pdf` and removing the test annotations (i.e., unrelated with `a-few-annotations.pdf`); uncompressed size is 144 MB
