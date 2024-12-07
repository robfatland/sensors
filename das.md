[sensors repository home](http://github.com/robfatland/sensors)


## USGS article: Seismology in the cloud; a new streaming workflow


MacCarthy, Jonathan, Marcillo, Omar, Trabant, Chad


Seismological research letters, 2020, Vol.91 (3), p.1804-1812


#### Description


Data-intensive research in seismology is experiencing a recent boom, driven in part by large 
volumes of available data and advances in the growing field of data science. However, there 
are significant barriers to processing large data volumes, such as long retrieval times from 
data repositories, complex data management, and limited computational resources. New tools 
and platforms have reduced the barriers to entry for scientific cluster computing, including 
the maturation of the commercial cloud as an accessible instrument for research. In this 
work, we build a customized research cluster in the cloud to test a new workflow for 
large-scale seismic analysis, in which data are processed as a stream (retrieved on-the-fly 
and acted upon without storing), with data from the Incorporated Research Institutions 
for Seismology Data Management Center. We use this workflow to deploy a spectral peak 
detection algorithm over 5.6 TB of compressed continuous seismic data from 2074 stations 
of the USArray Transportable Array EarthScope network. Using a 50-node cluster in the 
cloud, we completed the noise survey in 80 hr, with an average data throughput of 1.7 GB 
per minute. By varying cluster sizes, we find the scaling of our analysis to be sublinear, 
due to a combination of algorithmic limitations and data center response times. The 
cloud-based streaming workflow represents an order-of-magnitude increase in acquisition 
and processing speed compared to a traditional download-store-process workflow, and offers 
the additional benefits of employing a flexible, accessible, and widely used computing 
architecture. It is limited, however, due to its reliance on Internet transfer speeds 
and data center service capacity, and may not work well for repeated analyses or those 
for which even higher data throughputs are needed. These research applications will 
require a new class of cloud-native approaches in which both data and analysis are in the cloud.

#### Metadata

- United States: Seismological Society of America
- Identifier
- ISSN: 0895-0695
- EISSN: 1938-2057
- DOI: 10.1785/0220190357


## QuakeFlow: a scalable machine-learning-based earthquake monitoring workflow with cloud computing


- Zhu, Weiqiang and 6 others
- Geophysical journal international, 2022, Vol.232 (1), p.684-693


#### Description

SUMMARY Earthquake monitoring workflows are designed to detect earthquake signals and 
to determine source characteristics from continuous waveform data. Recent developments 
in deep learning seismology have been used to improve tasks within earthquake 
monitoring workflows that allow the fast and accurate detection of up to orders 
of magnitude more small events than are present in conventional catalogues. To 
facilitate the application of machine-learning algorithms to large-volume seismic 
records at scale, we developed a cloud-based earthquake monitoring workflow, 
QuakeFlow, which applies multiple processing steps to generate earthquake catalogues 
from raw seismic data. QuakeFlow uses a deep learning model, PhaseNet, for picking 
P/S phases and a machine learning model, GaMMA, for phase association with 
approximate earthquake location and magnitude. Each component in QuakeFlow is 
containerized, allowing straightforward updates to the pipeline with new deep 
learning/machine learning models, as well as the ability to add new components, 
such as earthquake relocation algorithms. We built QuakeFlow in Kubernetes to 
make it auto-scale for large data sets and to make it easy to deploy on cloud 
platforms, which enables large-scale parallel processing. We used QuakeFlow to 
process three years of continuous archived data from Puerto Rico within a few 
hours, and found more than a factor of ten more events that occurred on much 
the same structures as previously known seismicity. We applied Quakeflow to 
monitoring earthquakes in Hawaii and found over an order of magnitude more 
events than are in the standard catalogue, including many events that illuminate 
the deep structure of the magmatic system. We also added Kafka and Spark streaming 
to deliver real-time earthquake monitoring results. QuakeFlow is an effective 
and efficient approach both for improving real-time earthquake monitoring and 
for mining archived seismic data sets.


#### Metadata


- Publisher
- Ithaca: Oxford University Press
- Identifier
- ISSN: 0956-540X
- EISSN: 1365-246X
- EISSN: 2331-8422
- DOI: 10.1093/gji/ggac355


## Distributed acoustic sensing turns fiber-optic cables into sensitive seismic antennas


Author Zhan, Zhongwen


Seismological research letters, 2019, Vol.91 (1), p.1-15


#### Description


Distributed acoustic sensing (DAS) is a new, relatively inexpensive technology that 
is rapidly demonstrating its promise for recording earthquake waves and other seismic 
signals in a wide range of research and public safety arenas. It should significantly 
augment present seismic networks. For several important applications, it should be 
superior. It employs ordinary fiber-optic cables, but not as channels for data among 
separate sophisticated instruments. With DAS, the hair-thin glass fibers themselves 
are the sensors. Internal natural flaws serve as seismic strainmeters, kinds of 
seismic detector. Unused or dark fibers are common in fiber cables widespread around 
the globe, or in dedicated cables designed for special application, are appropriate 
for DAS. They can sample passing seismic waves at locations every few meters or 
closer along paths stretching for tens of kilometers. DAS arrays should enrich the 
three major areas of local and regional seismology: earthquake monitoring, imaging 
of faults and many other geologic formations, and hazard assessment. Recent 
laboratory and field results from DAS tests underscore its broad bandwidth and 
high-waveform fidelity. Thus, while still in its infancy, DAS already has shown 
itself as the working heart-or perhaps ear drums-of a valuable new seismic listening 
tool. My colleagues and I expect rapid growth of applications. We further expect it 
to spread into such frontiers as ocean-bottom seismology, glacial and related 
cryoseismology, and seismology on other solar system bodies.


#### Publisher
- Seismological Society of America
- Identifier
- ISSN: 0895-0695
- EISSN: 1938-2057
- DOI: 10.1785/0220190112


## Spica, Z. J., et al. PubDAS: a PUBlic Distributed Acoustic Sensing datasets repository for geosciences.


[Eartharxiv preprint](https://eartharxiv.org/repository/view/3574/)


## High‐performance IO for seismic processing on the cloud


#### Authors


Guimarães, Antonio; Lacalle, Luis; Rodamilans, Charles B.; Borin, Edson


Concurrency and computation, 2021, Vol.33 (18), p.n/a


#### Description


Summary Most of the applications in the seismology field rely on the processing of up to hundreds of terabytes of data and their performance is strongly affected by IO operations. In this article, we analyze the main file structures currently used to store seismic data and propose a new intermediate data structure to improve IO performance while still complying with established standards. We show that, throughout a common workflow in seismic data analysis, our IO performance gain greatly surpasses the overhead of translating data to the intermediate structure. This approach enables a speedup of up to 208 times in reading time when using classical standards (e.g., SEG‐Y) and our intermediate structure is up to 1.8 times more efficient than modern formats (e.g., ASDF). Considering cache‐friendly applications, our speedups over the direct use of SEG‐Y reach 8000 times. We also performed a cost analysis on the AWS cloud showing that, in our approach, HDDs can be 1.25 times more cost‐effective than SSDs.


#### Publisher


- Hoboken: Wiley Subscription Services, Inc
- Identifier
- ISSN: 1532-0626
- EISSN: 1532-0634
- DOI: 10.1002/cpe.6250



## Ground vibrations recorded by fiber-optic cables reveal traffic response to COVID-19 lockdown measures in Pasadena, California


#### Authors


Wang, Xin; Zhan, Zhongwen; Williams, Ethan F.; Herráez, Miguel González; Martins, Hugo Fidalgo; Karrenbach, Martin;


Communications earth & environment, 2021, Vol.2 (1), p.1-9


#### Description


Abstract The COVID-19 lockdown has unprecedently affected the dynamics of our society. As traffic flow is a good proxy for societal activity, traffic monitoring becomes a useful tool to assess the lockdown’s impacts. Here we turned two strands of unused telecommunication fibers in Pasadena, California into a seismic array of ~5,000 sensors and detected ground vibrations caused by moving vehicles along the streets above the cable. We monitor the number of vehicles and their mean speed between December 2019 and August 2020 in high spatial and temporal resolution, and then analyze the traffic patterns change due to the COVID-19 lockdown. Our results show a city-wide decline in traffic volume and an increase in speed due to the lockdown, although the level of impact varies substantially by streets. This study demonstrates the feasibility of using telecommunication fiber optic cables in traffic monitoring, which has implications for public health, economy, and transportation safety.


#### Publisher


- London: Nature Publishing Group
- Identifier
- ISSN: 2662-4435
- EISSN: 2662-4435
- DOI: 10.1038/s43247-021-00234-3



## Sub‐Kilometer Correlation Between Near‐Surface Structure and Ground Motion Measured With Distributed Acoustic Sensing


#### Authors


Yang, Yan; Atterholt, James W. ; Shen, Zhichao ; Muir, Jack B. ; Williams, Ethan F. ; Zhan, Zhongwen


Geophysical research letters, 2022, Vol.49 (1), p.n/a


#### Description


Earthquake ground motion depends strongly on near‐surface structure, which is challenging to image in urban areas at high resolution. Distributed acoustic sensing (DAS) is an emerging technique that provides a scalable solution by converting preexisting fiber‐optic cables into dense seismic arrays. After the July 2019 M7.1 Ridgecrest earthquake, we converted an underground dark fiber across the city of Ridgecrest, CA, into a DAS array. The recorded aftershocks show substantial lateral variability in site amplification over only 8‐km in distance. To understand the cause of such variability, we used three months of continuous data, dominated by traffic‐generated seismic noise, to image near‐surface structure along the fiber path. We find that the lateral variations of earthquake shaking correlate well with the shallow shear velocity model at sub‐kilometer scales, in particular micro‐basins filled with soft sediments. These results highlight the great potential of DAS for high‐resolution seismic hazard mapping in urban areas. Plain Language Summary Earthquake shaking is often highly variable in space. Yet, the physics behind this variability is not entirely clear, partially because high‐resolution instrumental observations are rare. Distributed acoustic sensing (DAS) is an emerging technique that can turn existing fiber‐optic cables into cost‐effective seismic arrays with meter‐scale spacing. After the Ridgecrest M7.1 earthquake in July 2019, we repurposed a 10‐km unused telecom fiber in the city of Ridgecrest, CA, as a 1250‐sensor DAS array and recorded thousands of aftershocks within three months. The aftershock data reveal significant variation of ground shaking over short distances. We used seismic noise generated by traffic along the same cable to image the near‐surface structure, which correlates well with the earthquake shaking intensity. Our findings show that DAS is a valuable tool for seismic hazard mapping in urban areas. Key Points We established a DAS array to capture the aftershocks of the 2019 M7.1 Ridgecrest earthquake and continuous traffic noise Earthquakes recorded by the DAS array show notable lateral variation of ground acceleration, after conversions from strain The Vs30 profile imaged by DAS ambient noise interferometry correlates well with the site terms at sub‐kilometer scales


#### Publisher


- Washington: Blackwell Publishing Ltd
- Identifier
- ISSN: 0094-8276
- EISSN: 1944-8007
- DOI: 10.1029/2021GL096503
