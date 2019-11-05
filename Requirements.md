List of Requirements for the SOL Project (split by user base)

Overall requirements:
⋅⋅*Yocto Based for Jetson TX2i
⋅⋅*Target of < 256 MB not counting language support
⋅⋅*Preempt-rt patch
⋅⋅*Ram based file system
⋅⋅*No peripherals except USB, Serial and Ethernet
⋅⋅*Docker required
⋅⋅*ECC
⋅⋅*NVPModel
⋅⋅*Single Event Upset logging (we think we can crawl dmesg and identify when we get hit, which would be wildly useful for us)
 
Languages supported:
⋅⋅*CUDA 10
⋅⋅*Python 3
⋅⋅*Rust
⋅⋅*Go
⋅⋅*C (GCC 7 I think is what CUDA 10 needs)
⋅⋅*Need to identify which packages are required to be built in for each language OR if we are able to have a user defined /home directory on flash that allows us to have run time libraries.


UGA specific requirements:

APL specific requirements:

Spire Global specific requirements:

Quick2Space specific requirements:
