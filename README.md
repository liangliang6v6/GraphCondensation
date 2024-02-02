# Graph Condensation Dataset Statics

In order to facilitate further experimental research in the field, we have compiled a dataset of commonly used GC methods, with links to jump directly to the specific methods.

## Single Graph

| Dataset                                                      | #Nodes    | #Edges      | #Features | #Classes | Type                  |
| ------------------------------------------------------------ | --------- | ----------- | --------- | -------- | --------------------- |
| [Cora](https://arxiv.org/pdf/2110.07580.pdf)                 | 2,708     | 5,429       | 1,433     | 7        | Citation              |
| [CoraFull](https://arxiv.org/pdf/2309.09455.pdf)             | 19,793    | 130,622     | 8,710     | 70       | Citation              |
| [Citeseer](https://arxiv.org/pdf/2110.07580.pdf)             | 3,327     | 4,732       | 3,703     | 6        | Citation              |
| [Citeseer-L](https://arxiv.org/pdf/2310.09192.pdf)           | 3,327     | 4,732       | 3,703     | 2        | Citation              |
| [DBLP](https://arxiv.org/pdf/2106.05150.pdf)                 | 17,716    | 52,867      | 1,639     | 4        | Citation              |
| [DBLP-large](https://arxiv.org/pdf/2310.09192.pdf)           | 26,128    | 105,734     | 4,057     | 2        | Citation              |
| [Coauthor Physics(Co-phy)](https://arxiv.org/pdf/2106.05150.pdf) | 34,493    | 247,692     | 8,415     | 5        | Citation              |
| [OGBNArxiv(Arixiv)](https://arxiv.org/pdf/2110.07580.pdf)    | 169,343   | 1,166,243   | 128       | 40       | Citation              |
| [Pubmed](https://arxiv.org/pdf/2206.07746.pdf)               | 19,717    | 44,338      | 500       | 3        | Citation              |
| [OGBLCitation2](https://arxiv.org/pdf/2312.15520.pdf)        | 2,927,963 | 30,561,187  | 128       | N/A      | Citation              |
| [ACM](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 3,025     | 13,128      | 1,870     | N/A      | Citation              |
| [Friendster](https://arxiv.org/pdf/1910.02370.pdf)           | 7,944,949 | 446,673,688 | N/A       | 5000     | Social                |
| [Flickr](https://arxiv.org/pdf/2110.07580.pdf)               | 89,250    | 899,756     | 500       | 7        | Social                |
| [Reddit](https://arxiv.org/pdf/2110.07580.pdf)               | 232,965   | 57,307,946  | 602       | 210      | Social                |
| [Reddit-A](https://arxiv.org/pdf/2307.15967.pdf)             | 232,965   | 11,606,919  | 602       | 41       | Social                |
| [Reddit-B](https://arxiv.org/pdf/2309.09455.pdf)             | 227,853   | 114,615,892 | 602       | 40       | Social                |
| [Genius](https://www.sciencedirect.com/science/article/pii/S0950705123006548) | 42,1961   | 984,979     | 12        | 2        | Social                |
| [YelpChi](https://arxiv.org/pdf/2310.09192.pdf)              | 45,954    | 3,846,979   | 32        | 2        | Social                |
| [Polblogs](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 1,490     | 16,715      | 5,000     | N/A      | Social                |
| [PPI](https://arxiv.org/pdf/1910.02370.pdf)                  | 14,755    | 222,055     | 50        | 121      | Biology               |
| [Yeast](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 2,361     | 13,292      | 5,000     | N/A      | Biology               |
| [Airfoil](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 4,253     | 12,289      | 5,000     | N/A      | Transportation        |
| [Minnesota](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 2,642     | 3,304       | 5000      | N/A      | Transportation        |
| [Bunny](https://proceedings.mlr.press/v202/kumar23a/kumar23a.pdf) | 2,503     | 78,292      | 5,000     | N/A      | Point cloud           |
| [OGBLCollab](https://arxiv.org/pdf/2312.15520.pdf)           | 235,868   | 1,285,465   | 128       | N/A      | Collaboration         |
| [OGBNProducts](https://arxiv.org/pdf/2312.15520.pdf)         | 2,449,029 | 61,859,140  | 128       | 47       | Product|
| [Products](https://arxiv.org/pdf/2309.09455.pdf)             | 2,449,029 | 61,859,140  | 100       | 46       | Product|
| [Amazon](https://arxiv.org/pdf/2310.09192.pdf)               | 11,944    | 4,398,392   | 25        | 2        | Product               |

## Multiple Graph

| Dataset                                              | #Graphs | #Avg.Nodes | #Avg.Edges | #Classes | Type        |
| ---------------------------------------------------- | ------- | ---------- | ---------- | -------- | ----------- |
| [CIFAR10](https://arxiv.org/pdf/2206.07746.pdf)      | 60,000  | 117.6      | 941.07     | 10       | Superpixel  |
| [ogbg-molhiv](https://arxiv.org/pdf/2206.07746.pdf)  | 41,127  | 25.5       | 54.9       | 2        | Molecule    |
| [ogbg-molbace](https://arxiv.org/pdf/2206.07746.pdf) | 1,513   | 34.1       | 36.9       | 2        | Molecule    |
| [ogbg-molbbbp](https://arxiv.org/pdf/2206.07746.pdf) | 2,039   | 24.1       | 26.0       | 2        | Molecule    |
| [MUTAG](https://arxiv.org/pdf/2206.07746.pdf)        | 188     | 17.93      | 19.79      | 2        | Molecule    |
| [NCI1](https://arxiv.org/pdf/2206.07746.pdf)         | 4,110   | 29.87      | 32.30      | 2        | Molecule    |
| [DD](https://arxiv.org/pdf/2206.07746.pdf)           | 1,178   | 284.32     | 715.66     | 2        | Molecule    |
| [ENZYMES](https://arxiv.org/pdf/1802.04447.pdf)      | 600     | 32.63      | 62.14      | 6        | Molecule    |
| [NCI109](https://arxiv.org/pdf/1802.04447.pdf)       | 4,127   | 29.68      | 32.13      | 2        | Molecule    |
| [PROTEINS](https://arxiv.org/pdf/1802.04447.pdf)     | 1,108   | 39.06      | 72.70      | 2        | Molecule    |
| [PTC](https://arxiv.org/pdf/1802.04447.pdf)          | 344     | 14.29      | 14.69      | 2        | Molecule    |
| [IMDB-BINARY](https://arxiv.org/pdf/1912.11176.pdf)  | 1,000   | 19.8       | 96.5       | 2        | Social      |
| [IMDB-MULTI](https://arxiv.org/pdf/1912.11176.pdf)   | 1,500   | 13.0       | 65.9       | 3        | Social      |
| [E-commerce](https://arxiv.org/pdf/2206.07746.pdf)   | 1,109   | 33.7       | 46.3       | 2        | Transaction |

