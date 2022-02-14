## SCU-Net: A deep learning method for segmentation and quantification of breast arterial calcifications on mammograms

Code for breast arterial calcifications segmentation on mammograms of the following paper: SCU-Net: A deep learning method for segmentation and quantification of breast arterial calcifications on mammograms (https://pubmed.ncbi.nlm.nih.gov/34328661/, https://www.medrxiv.org/content/10.1101/2021.07.30.21261406v1.full.pdf).


## Usage:

Download the code:

``` shell
git clone http://github.com/XiaoyuanGuo/BAC_segmentation/
``` 

The full list of required Python Packages is available in requrirements.txt file. It is possible to install all the dependencies by:

``` shell
pip install -r requirements.txt 
``` 

To train the model:  
``` shell
python main.py
``` 
### An evaluation version of SCU-Net can be found: https://github.com/Emory-HITI/BAC_segmentation

### Cite SCU-Net

If you use this repository or would like to refer the paper, please use the following BibTeX entry
```
@article{guo2021scu,
  title={SCU-Net: A deep learning method for segmentation and quantification of breast arterial calcifications on mammograms},
  author={Guo, Xiaoyuan and O'Neill, W Charles and Vey, Brianna and Yang, Tianen Christopher and Kim, Thomas J and Ghassemi, Maryzeh and Pan, Ian and Gichoya, Judy Wawira and Trivedi, Hari and Banerjee, Imon},
  journal={Medical physics},
  volume={48},
  number={10},
  pages={5851--5861},
  year={2021},
  publisher={Wiley Online Library}
}
```
