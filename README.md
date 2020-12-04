# Highspeed MRIQC

## Overview

This repository contains binarized anatomical masks used in Wittkuhn & Schuck, 2020, *Nature Communications*.

Please see the paper and the project website at https://wittkuhn.mpib.berlin/highspeed/ for further details about the study.
The meta-data of this dataset are available at https://github.com/lnnrtwttkhn/highspeed-masks and the data contents at https://gin.g-node.org/lnnrtwttkhn/highspeed-masks.

## Dataset structure

- Anatomical binarized masks are in `masks/`
- All inputs (i.e. building blocks from other sources) are located in
  `fmriprep/` and `/bids`.
- All custom code is located in `code/`.

## Run code

Install required packages:

```bash
mkvirtualenv -p $(which python3) highspeed-masks
pip install -r requirements.txt
```

## Contact

- [Lennart Wittkuhn](mailto:wittkuhn@mpib-berlin.mpg.de)
- [Nicolas W. Schuck](mailto:schuck@mpib-berlin.mpg.de)

## License

Please see the [LICENSE](LICENSE) file for details.
