# gvp-hdr-tools
HDR PQ/HLG Tools

This project provides a set of tools to define PQ and HLG HDR systems
and make conversions between these two formats.

These systems are defined in ITU-R BT.2100, which is based on BT.2390

PQ is a display-referred system,so it's defined by its EOTF. PQ OETF
is defined by the concatenation of the OOTF and its inverse EOTF.

    http://www.text-image.com/samples/text-face.gif  
 
           

HLG is a scene-referred system,so it's defined by its OETF. PQ EOTF
is defined by the concatenation of its inverse OETF and the OOTF.


