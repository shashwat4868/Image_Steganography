# Image_Steganography
### Image Steganography using an Edge Based Embedding Technique - 
* The aim of this project is to execute a information hiding method based on Edge Embedding Technique and LSB (Least Significant Bit) Technique on digital images. Moreover, traditional AES Encryption is also performed to provide an extra level of security to the information before embedding it to the digital image making it very tough for attackers to decode the actual piece of information from just a simple looking image.

### Methodology -
1. Text Compression:  Huffman coding will be used for the purpose of minimization of tree nodes and leading to compression of text.
2. AES Encryption:    The text is divided into 128-bit blocks and encrypted with 10 rounds in ECB mode then the results of the encryption are appended to get encrypted text.
3. Text Embedding in Image: Edge based approach is used where the LSB of each pixel is changed to have minimum affect on the original image.
