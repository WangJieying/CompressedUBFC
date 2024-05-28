# CompressedUBFC
Remote photoplethysmography (rPPG) has recently attracted much attention due to its non-contact measurement convenience and great potential in health care and computer vision applications. Early rPPG methods were mostly based on self collected uncompressed video data, which greatly limited their application in scenarios that require long-distance real-time video transmission, and also hindered the generation of large-scale publicly available benchmark datasets.
%, as uncompressed video would occupy a large amount of hard disk space.
In recent years, with the popularization of high-definition video and the rise of telemedicine, the pressure of storage and real-time video transmission under limited bandwidth have made the compression of rPPG video inevitable.
However, video compression can adversely affect rPPG measurements. This is due to the fact that conventional video compression algorithms are not specifically designed to preserve physiological signals. 
Instead, video compression is precisely about removing this pulsating information embedded in the tiny color changes in the skin that are imperceptible to the human eye.
Based on this, we propose a video compression scheme specifically for rPPG application, which provide quasi-lossless compression of the physiological information contained in the original video while ensuring visual effects and high compression rates. 

We provide an alternate version of the UBFC dataset (68 GB in total), which compresses the file size to about 1 GB while preserving almost all of the physiological information. All compressed videos are obtained in [releases](https://github.com/WangJieying/CompressedUBFC/releases).
