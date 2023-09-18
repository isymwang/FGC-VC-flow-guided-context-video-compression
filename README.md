# FGC-VC-flow-guided-context-video-compression [ICIP2023(Oral)]

![overview.jpg](https://github.com/isymwang/FGC-VC-flow-guided-context-video-compression/blob/main/Fig/overview.jpg)


Deep video compression has attracted more and more attention in recent years. Previous works rely on feature space operations, which may cause the offset maps overflow degrading reconstructed frame quality. In this work, we propose a flowguided module to guide the offset maps learning explicitly and alleviate offset maps overflow. Moreover, we introduce a context scheme to explore the temporal prior and fuse the hyper prior model to improve the compression ratio. For coding speed, we drop the time-consuming auto regressive module. Experimental results demonstrate that our method outperforms the previous learning-based schemes and traditional codecs. Compared to x265 with medium preset, our approach brings average 38.53% and 54.67% bit rate savings in PSNR and MS-SSIM metrics, respectively.

## Acknowledgement
    The implementation is based on CompressAI and PyTorchVideoCompression.



Code will be uploaded in the future
