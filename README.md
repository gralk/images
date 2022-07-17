# Scene-Referred Image Collection
A collection of OpenEXR Scene-Referred images, encoded as max 2048px width, DWAA 80 compression.

All exrs are encoded Filmlight E-Gamut linear. To convert from E-Gamut to XYZ you can use this 3x3 matrix.

```
0.7053968501 0.1640413283 0.08101774865
0.2801307241 0.8202066415 -0.1003373656
-0.1037815116 -0.07290725703 1.265746519
```

or, as a Nuke ColorMatrix node:
```
ColorMatrix {
 matrix {
     {0.7053968501 0.1640413283 0.08101774865}
     {0.2801307241 0.8202066415 -0.1003373656}
     {-0.1037815116 -0.07290725703 1.265746519}
   }
 label "Filmlight E-Gamut to XYZ D65"
}
```

## Sources

These images were acquired from the following open sources:

- [ACES Gamut Mapping Virtual Working Group Image Submissions](https://www.dropbox.com/sh/u6z2a0jboo4vno8/AAB-10qcflhpr0C5LWhs7Kq4a)  
- [ACES Output Transform Image Submissions](https://www.dropbox.com/sh/zea11rkxkivv7w7/AADM8TB9tmpI9qdLB5JvRb-ra)  
- [Arri Camera Sample Footage](https://www.arri.com/en/learn-help/learn-help-camera-system/camera-sample-footage)  
- [Red Sample R3D Files](https://www.red.com/sample-r3d-files)  
- [Stuttgart Visual Media Lab HDR Test Footage](https://www.hdm-stuttgart.de/vmlab/hdm-hdr-2014/#FTPdownload)  
- [Blackmagic Raw Test Footage](https://www.blackmagicdesign.com/ca/products/blackmagicpocketcinemacamera/gallery)  


## File List in **exr** folder

```
SRIC_arri.01001.exr
SRIC_arri.01002.exr
SRIC_arri.01003.exr
SRIC_arri.01004.exr
SRIC_arri.01005.exr
SRIC_arri.01006.exr
SRIC_arri.01007.exr
SRIC_arri.01008.exr
SRIC_arri.01009.exr
SRIC_arri.01010.exr
SRIC_arri.01011.exr
SRIC_arri.01012.exr
SRIC_arri.01013.exr
SRIC_arri.01014.exr
SRIC_arri.01015.exr
SRIC_arri.01016.exr
SRIC_arri.01017.exr
SRIC_arri.01018.exr
SRIC_arri.01019.exr
SRIC_arri_alexa35.01001.exr
SRIC_arri_alexa35.01002.exr
SRIC_arri_alexa35.01003.exr
SRIC_arri_alexa35.01004.exr
SRIC_arri_alexa35.01005.exr
SRIC_arri_alexa35.01006.exr
SRIC_arri_alexa35.01007.exr
SRIC_arri_alexa35.01008.exr
SRIC_arri_alexa35.01009.exr
SRIC_arri_alexa35.01010.exr
SRIC_arri_alexa35.01011.exr
SRIC_arri_alexa35.01012.exr
SRIC_arri_alexa35.01013.exr
SRIC_arri_alexa35.01014.exr
SRIC_arri_alexa35.01015.exr
SRIC_arri_alexa35.01016.exr
SRIC_arri_alexa35.01017.exr
SRIC_arri_alexa35.01018.exr
SRIC_arri_alexa35.01019.exr
SRIC_arri_alexa35.01020.exr
SRIC_arri_alexa35.01021.exr
SRIC_arri_alexa35.01022.exr
SRIC_arri_alexa35.01023.exr
SRIC_arri_alexa35.01024.exr
SRIC_arri_alexa35.01025.exr
SRIC_arri_alexa35.01026.exr
SRIC_arri_alexa35.01027.exr
SRIC_arri_alexa35.01028.exr
SRIC_arri_alexa35.01029.exr
SRIC_arri_alexa35.01030.exr
SRIC_arri_alexa35.01031.exr
SRIC_arri_alexa35.01032.exr
SRIC_arri_alexa35.01033.exr
SRIC_arri_alexa35.01034.exr
SRIC_arri_alexa35.01035.exr
SRIC_arri_alexa35.01036.exr
SRIC_arri_alexa35.01037.exr
SRIC_arri_alexa35.01038.exr
SRIC_arri_alexa35.01039.exr
SRIC_arri_alexa35.01040.exr
SRIC_arri_alexa35.01041.exr
SRIC_arri_alexa35.01042.exr
SRIC_cinematography-mailing-list.01001.exr
SRIC_cinematography-mailing-list.01002.exr
SRIC_cinematography-mailing-list.01003.exr
SRIC_cinematography-mailing-list.01004.exr
SRIC_cinematography-mailing-list.01005.exr
SRIC_cinematography-mailing-list.01006.exr
SRIC_cinematography-mailing-list.01007.exr
SRIC_cinematography-mailing-list.01008.exr
SRIC_cinematography-mailing-list.01009.exr
SRIC_hdm-vmlab-hdr.01001.exr
SRIC_hdm-vmlab-hdr.01002.exr
SRIC_hdm-vmlab-hdr.01003.exr
SRIC_hdm-vmlab-hdr.01004.exr
SRIC_hdm-vmlab-hdr.01005.exr
SRIC_hdm-vmlab-hdr.01006.exr
SRIC_hdm-vmlab-hdr.01007.exr
SRIC_hdm-vmlab-hdr.01008.exr
SRIC_hdm-vmlab-hdr.01009.exr
SRIC_hdm-vmlab-hdr.01010.exr
SRIC_hdm-vmlab-hdr.01011.exr
SRIC_hdm-vmlab-hdr.01012.exr
SRIC_hdm-vmlab-hdr.01013.exr
SRIC_hdm-vmlab-hdr.01014.exr
SRIC_hdm-vmlab-hdr.01015.exr
SRIC_hdm-vmlab-hdr.01016.exr
SRIC_hdm-vmlab-hdr.01017.exr
SRIC_hdm-vmlab-hdr.01018.exr
SRIC_hdm-vmlab-hdr.01019.exr
SRIC_hdm-vmlab-hdr.01020.exr
SRIC_hdm-vmlab-hdr.01021.exr
SRIC_hdm-vmlab-hdr.01022.exr
SRIC_hdm-vmlab-hdr.01023.exr
SRIC_hdm-vmlab-hdr.01024.exr
SRIC_hdm-vmlab-hdr.01025.exr
SRIC_hdm-vmlab-hdr.01026.exr
SRIC_hdm-vmlab-hdr.01027.exr
SRIC_hdm-vmlab-hdr.01028.exr
SRIC_hdm-vmlab-hdr.01029.exr
SRIC_hdm-vmlab-hdr.01030.exr
SRIC_hdm-vmlab-hdr.01031.exr
SRIC_hdm-vmlab-hdr.01032.exr
SRIC_hdm-vmlab-hdr.01033.exr
SRIC_hdm-vmlab-hdr.01034.exr
SRIC_hdm-vmlab-hdr.01035.exr
SRIC_hdm-vmlab-hdr.01036.exr
SRIC_hdm-vmlab-hdr.01037.exr
SRIC_hdm-vmlab-hdr.01038.exr
SRIC_hdm-vmlab-hdr.01039.exr
SRIC_hdm-vmlab-hdr.01040.exr
SRIC_hdm-vmlab-hdr.01041.exr
SRIC_hdm-vmlab-hdr.01042.exr
SRIC_hdm-vmlab-hdr.01043.exr
SRIC_hdm-vmlab-hdr.01044.exr
SRIC_hdm-vmlab-hdr.01045.exr
SRIC_hdm-vmlab-hdr.01046.exr
SRIC_hdm-vmlab-hdr.01047.exr
SRIC_red.01001.exr
SRIC_red.01002.exr
SRIC_red.01003.exr
SRIC_red.01004.exr
SRIC_red.01005.exr
SRIC_red.01006.exr
SRIC_red.01007.exr
SRIC_red.01008.exr
SRIC_red.01009.exr
SRIC_red.01010.exr
SRIC_red.01011.exr
SRIC_red.01012.exr
SRIC_vwg_gamut-mapping.01001.exr
SRIC_vwg_gamut-mapping.01002.exr
SRIC_vwg_gamut-mapping.01003.exr
SRIC_vwg_gamut-mapping.01004.exr
SRIC_vwg_gamut-mapping.01005.exr
SRIC_vwg_gamut-mapping.01006.exr
SRIC_vwg_gamut-mapping.01007.exr
SRIC_vwg_gamut-mapping.01008.exr
SRIC_vwg_gamut-mapping.01009.exr
SRIC_vwg_gamut-mapping.01010.exr
SRIC_vwg_gamut-mapping.01011.exr
SRIC_vwg_gamut-mapping.01012.exr
SRIC_vwg_gamut-mapping.01013.exr
SRIC_vwg_gamut-mapping.01014.exr
SRIC_vwg_gamut-mapping.01015.exr
SRIC_vwg_gamut-mapping.01016.exr
SRIC_vwg_gamut-mapping.01017.exr
SRIC_vwg_gamut-mapping.01018.exr
SRIC_vwg_gamut-mapping.01019.exr
SRIC_vwg_gamut-mapping.01020.exr
SRIC_vwg_output-transforms.01001.exr
SRIC_vwg_output-transforms.01002.exr
SRIC_vwg_output-transforms.01003.exr
SRIC_vwg_output-transforms.01004.exr
SRIC_vwg_output-transforms.01005.exr
SRIC_vwg_output-transforms.01006.exr
SRIC_vwg_output-transforms.01007.exr
SRIC_vwg_output-transforms.01008.exr
SRIC_vwg_output-transforms.01009.exr
SRIC_vwg_output-transforms.01010.exr
SRIC_vwg_output-transforms.01011.exr
SRIC_vwg_output-transforms.01012.exr
SRIC_vwg_output-transforms.01013.exr
SRIC_vwg_output-transforms.01014.exr
SRIC_vwg_output-transforms.01015.exr

```