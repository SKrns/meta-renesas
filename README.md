# This branch is only for Perseus Inc. and r8a77965(m3nulcb, salvator-x)

Already installed Multimedia, Graphics library, and Linux drivers(20190507) for
	
	R-Car Gen3 Evaluation Software Package for Linux for Yocto v3.19.0 and Wayland 1.13 /Weston 2.0
Layer modifier: GwonSH <soon3626@cyberperseus.com>

## OpenEmbedded/Yocto BSP layer for Renesas Electronics's SoCs

This layer provides support for Renesas Electronics's platforms for use with
OpenEmbedded and/or Yocto.

Layer maintainer: Takamitsu Honda <takamitsu.honda.pv@renesas.com>

## Supported Boards/Machines


In addition, this also provides layer which supports boards using Renesas SoCs.
Layer and boards that support is the following:

    meta-rcar-gen3
        - Renesas Electronics Corporation. Salvator-X (R8A7795/R8A7796/R8A77965)
        - Renesas Electronics Corporation. R-Car Starter Kit premier(H3ULCB) (R8A7795)
        - Renesas Electronics Corporation. R-Car Starter Kit pro(M3ULCB) (R8A7796)
        - Renesas Electronics Corporation. R-Car Starter Kit pro(M3NULCB) (R8A77965)
        - Renesas Electronics Corporation. R-Car Ebisu (R8A77990)

Please see README in the layer directory for the description of the board.

## Original BSP image

The meta-renesas layer provides original BSP image. The following:

* core-image-minimal
* core-image-weston
