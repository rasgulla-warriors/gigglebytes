# gigglebytes
---
## Data
### Unzipped Data:
* [2019](https://www.kaggle.com/datasets/namitaachyuthanpesu/unzipped-pcap-2019)
* [2018](https://www.kaggle.com/datasets/namitaachyuthanpesu/unzipped-pcap-2018)
* [2016](https://www.kaggle.com/datasets/namitaachyuthanpesu/unzipped-pcap-2016)
* [2015](https://www.kaggle.com/datasets/namitaachyuthanpesu/unzipped-pcap-2015)
* [2014](https://www.kaggle.com/datasets/namitaachyuthanpesu/unzipped-pcap-2014)

### Data Pushed into CSVs:
* [2019](https://www.kaggle.com/datasets/namitaachyuthanpesu/pcap-2019-dira-125910)
* [2018](https://www.kaggle.com/datasets/namitaachyuthanpesu/2018-pcap-to-csv)
* [2016](https://www.kaggle.com/datasets/namitaachyuthanpesu/2016-pcap-to-csv)
---
## Method of extraction: 
1. Main directory -> Year -> equinix data-> pass through ```final-pcap-gz.ipynb```
     * pcap.gz files were unzipped into different directories
2. Unzipped files were passed through ```losingMyMind.ipynb```
     * pcap files were split into 100MB chunks and then interated through
3. Regions differ across years: 2014-2016 are from Chicago, 2018-2019 are NY
---
## For prerequisites, just use ```requirements.txt```
