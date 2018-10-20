All credits: https://github.com/VisualComputingInstitute/triplet-reid, for all packages dependencies please refer to it.

To use it, overwrite img files in tracking-triplet_net/Triplet/triplet-reid/test_imgs and img names in tracking- triplet_net/Triplet/triplet-reid/files.txt.

Then download pre-trained model file [here](https://omnomnom.vision.rwth-aachen.de/data/trinet-mars.npz), put it in tracking-triplet_net/Triplet/triplet-reid

Then run python trinet_embed.py files.txt /path/to/trinet-mars.npz
