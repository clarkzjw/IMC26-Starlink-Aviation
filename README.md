# IMC'26: Measuring Starlink Aviation Around the World

This repository contains the dataset and artifacts associated with the paper ***[Measuring Starlink Aviation Around the World](https://dl.acm.org/doi/10.1145/3777912.3839781)***, published at the [2026 ACM Internet Measurement Conference (IMC '26)](https://conferences.sigcomm.org/imc/2026/).

If you use this repository or dataset in your research, please cite our paper:

<details>
<summary>BibTeX</summary>

```bibtex
@inproceedings{zhao2026starlinkaviation,
author = {Zhao, Jinwei and Pan, Jianping},
title = {Measuring Starlink Aviation Around the World},
year = {2026},
isbn = {9798400723278},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3777912.3839781},
doi = {10.1145/3777912.3839781},
booktitle = {Proceedings of the 2026 ACM Internet Measurement Conference},
pages = {1118–1132},
numpages = {15},
keywords = {LEO, starlink, aviation, in-flight connectivity, MPLS},
location = {Karlsruhe Institute of Technology, Karlsruhe, Germany},
series = {IMC '26}
}
```

</details>

## Datasets

> ***Note: The dataset upload will be completed no later than the date of the conference.***

### Paper Result

The [`paper-result`](./paper-result/) folder in this repository contains the accompaning data and scripts used to generate the figures in the paper.

This includes the `inside-out` latency and throughput measurements collected from WestJet flights, as well as the `outside-in` measurements related to the Qatar Airways case study as described in the paper.

### Starlink MPLS-to-PoP Mapping

The [mpls-label-to-pop.csv](https://github.com/clarkzjw/starlink-geoip-data/blob/master/mpls/mpls-label-to-pop.csv) file contains the SR-MPLS label-to-PoP mappings we have identified in Starlink's global backbone network. We publish this finding in the [starlink-geoip-data](https://github.com/clarkzjw/starlink-geoip-data) repository.

### Sample Datasets

We do not directly release the mapping between IPv6 router addresses and aircraft tail numbers due to the potential dual-use risks associated with such information.

The `sample` folder contains a small sample of the anycast-capable IPv6 router addresses for each airline, the `traceroute` measurements we collected, the extracted MPLS labels and the corresponding PoP code. The full `traceroute` or MPLS labels dataset is available upon request.

## License

This repository is licensed under [CC-BY-SA 4.0](https://github.com/clarkzjw/starlink-geoip-data/blob/master/LICENSE). Please cite our paper if you use this dataset in your research.

<details>
<summary>BibTeX</summary>

```bibtex
@inproceedings{zhao2026starlinkaviation,
author = {Zhao, Jinwei and Pan, Jianping},
title = {Measuring Starlink Aviation Around the World},
year = {2026},
isbn = {9798400723278},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3777912.3839781},
doi = {10.1145/3777912.3839781},
booktitle = {Proceedings of the 2026 ACM Internet Measurement Conference},
pages = {1118–1132},
numpages = {15},
keywords = {LEO, starlink, aviation, in-flight connectivity, MPLS},
location = {Karlsruhe Institute of Technology, Karlsruhe, Germany},
series = {IMC '26}
}
```

</details>