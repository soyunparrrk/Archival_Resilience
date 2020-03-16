# Image Compression and process

It is possible to compress many types of digital data in a way that reduces the size of a computer file needed to store it, or the bandwidth needed to transmit it, with no loss of the full information contained in the original file. A picture, for example, is converted to a digital file by considering it to be an array of dots and specifying the color and brightness of each dot. **If the picture contains an area of the same color, it can be compressed without loss by saying "200 red dots" instead of "red dot, red dot, ...(197 more times)..., red dot."**

→ Image converted into text and in again converts into image!? Interesting!

Methods for [lossy compression](https://en.wikipedia.org/wiki/Lossy_compression):

- [Transform coding](https://en.wikipedia.org/wiki/Transform_coding) – This is the most commonly used method.
    - [Discrete Cosine Transform](https://en.wikipedia.org/wiki/Discrete_Cosine_Transform) (DCT) – The most widely used form of lossy compression. It is a type of [Fourier-related transform](https://en.wikipedia.org/wiki/List_of_Fourier-related_transforms), and was originally developed by [Nasir Ahmed](https://en.wikipedia.org/wiki/N._Ahmed), T. Natarajan and [K. R. Rao](https://en.wikipedia.org/wiki/K._R._Rao) in 1974. The DCT is sometimes referred to as "DCT-II" in the context of a family of discrete cosine transforms (see [discrete cosine transform](https://en.wikipedia.org/wiki/Discrete_cosine_transform)). It is generally the most efficient form of image compression.

        [[2]](https://en.wikipedia.org/wiki/Image_compression#cite_note-2)

        - DCT is used in [JPEG](https://en.wikipedia.org/wiki/JPEG), the most popular lossy format, and the more recent [HEIF](https://en.wikipedia.org/wiki/HEIF).
    - The more recently developed [wavelet transform](https://en.wikipedia.org/wiki/Wavelet_transform) is also used extensively, followed by [quantization](https://en.wikipedia.org/wiki/Quantization_(image_processing)) and [entropy coding](https://en.wikipedia.org/wiki/Entropy_coding).
- Reducing the [color space](https://en.wikipedia.org/wiki/Color_space_encoding) to the most common colors in the image. The selected colors are specified in the colour [palette](https://en.wikipedia.org/wiki/Palette_(computing)) in the header of the compressed image. Each pixel just references the index of a color in the color palette, this method can be combined with [dithering](https://en.wikipedia.org/wiki/Dithering) to avoid [posterization](https://en.wikipedia.org/wiki/Posterization).
- [Chroma subsampling](https://en.wikipedia.org/wiki/Chroma_subsampling). This takes advantage of the fact that the human eye perceives spatial changes of brightness more sharply than those of color, by averaging or dropping some of the chrominance information in the image.
- [Fractal compression](https://en.wikipedia.org/wiki/Fractal_compression).

Methods for [lossless compression](https://en.wikipedia.org/wiki/Lossless_compression):

- [Run-length encoding](https://en.wikipedia.org/wiki/Run-length_encoding) – used in default method in [PCX](https://en.wikipedia.org/wiki/PCX) and as one of possible in [BMP](https://en.wikipedia.org/wiki/BMP_file_format), [TGA](https://en.wikipedia.org/wiki/.tga), [TIFF](https://en.wikipedia.org/wiki/TIFF)
- Area image compression
- Predictive coding – used in [DPCM](https://en.wikipedia.org/wiki/DPCM)
- [Entropy encoding](https://en.wikipedia.org/wiki/Entropy_encoding) – the two most common entropy encoding techniques are [arithmetic coding](https://en.wikipedia.org/wiki/Arithmetic_coding) and [Huffman coding](https://en.wikipedia.org/wiki/Huffman_coding)
- Adaptive dictionary algorithms such as [LZW](https://en.wikipedia.org/wiki/LZW) – used in [GIF](https://en.wikipedia.org/wiki/Graphics_Interchange_Format) and [TIFF](https://en.wikipedia.org/wiki/TIFF)
- [DEFLATE](https://en.wikipedia.org/wiki/DEFLATE) – used in [PNG](https://en.wikipedia.org/wiki/Portable_Network_Graphics), [MNG](https://en.wikipedia.org/wiki/Multiple-image_Network_Graphics), and [TIFF](https://en.wikipedia.org/wiki/TIFF)
- [Chain codes](https://en.wikipedia.org/wiki/Chain_code)