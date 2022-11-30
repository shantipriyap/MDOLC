# MDOLC
Multi Dialect Odia Song Lyric Corpus

The repository contains the code/data of the released Multi Dialect Odia Song Lyric Corpus (MDOLC). The data is already splitted into train/dev/test set for the experiment. We also provided 230 songs in XML format for research purposes.



Result
-------



Dependency
----------

Python 3.6

PyTorch (torch=1.0.1, torchtext=0.4.0, torchvision=0.4.0)

Utilities (Skopt, sklearn, numpy, Zipfile, Pandas, Pickel) 

How to Run ?
-------------
The dialect detection code supports both CPU/GPU. For running in CPU/GPU mode, enable/disable the "is_gpu" flag to "True" or "False" inside the "lang_detect_santali.py" file. 

Usage: Execute the following command on the command line to run using CPU:
```
python lang_detect_odia_samabalpuri.py
```


Contributor
------------
- [Shantipriya Parida](https://www.shantipriya.me/)
- Alakananda Tripathy
- [Satya Ranjan Dash](https://ksca.kiit.ac.in/profiles/satya-ranjan-dash/)
- Shashikanta Sahoo

Support/Contact
---------------
Please feel free to contact for any support or enhancement.


Citation
--------

If you found our research helpful or influential please consider citing

@inproceedings{parida-etal-2022-mdolc,
    title = "MDOLC: Multi Dialect Odia Song Lyric Corpus",
    author = {Parida, Shantipriya  and
      Tripathy, Alakananda   and
      Dash, Satya Ranjan   and
      Sahoo, Shashikanta},
    booktitle = "Proceedings of the International Conference on Recent Advancements in Artificial Intelligence and Soft Computing - ICAISC-2022",
    month = nov,
    year = "2022",
  }
