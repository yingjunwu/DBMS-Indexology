# DBMS Indexology

This repository contains a list of papers that focus on the design and implementation of index structures in modern database management systems (DBMSs). To better exhibit the design trend in this research area, this reading list is intended to only contain high-quality papers published in top-tier conferences/journals. If you have any paper in mind that you think awesome and would fit in this list, please feel free to send a [pull request](https://github.com/yingjunwu/DBMS-Indexology/pulls).

- - -

## Contents
- [Surveys](#surveys)
- [SSD-Based Tree Indexing](#ssd-based-tree-indexing)
- [NVM-Based Tree Indexing](#nvm-based-tree-indexing)
- [In-Memory Tree Indexing](#in-memory-tree-indexing)
- [Bitmap Indexing](#bitmap-indexing)
- [Hash Indexing](#hash-indexing)
- [Approximate Indexing](#approximate-indexing)

- - -

## Surveys
* D. Lomet, [The Evolution of Effective B-tree: Page Organization and Techniques: A Personal Account](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p64-lomet.pdf), in ACM SIGMOD Record, 2001.
* G. Graefe, [A Survey of B-Tree Locking Techniques](https://dl.acm.org/citation.cfm?id=1806907.1806908), in TODS, 2010.
* G. Graefe, [Modern B-tree techniques](https://www.nowpublishers.com/article/Details/DBS-028), in Foundations and Trends in Databases, 2011.

## HDD-Based Tree Indexing
* R. Bayer, et al., [Organization and Maintenance of Large Ordered Indices](https://infolab.usc.edu/csci585/Spring2010/den_ar/indexing.pdf), in SIGFIDET, 1970. _(original B-Tree paper)_
* R. Bayer, et al., [Prefix B-Trees](https://dl.acm.org/citation.cfm?id=320530), in TODS, 1977.

## SSD-Based Tree Indexing
* Y. Li, et al., [Tree Indexing on Solid State Drives](https://dl.acm.org/citation.cfm?id=1920990), in VLDB, 2010.

## NVM-Based Tree Indexing
* S. Chen, et al., [Persistent B+-Trees in Non-Volatile Main Memory](http://www.vldb.org/pvldb/vol8/p786-chen.pdf), in VLDB, 2015.
* I. Oukid, et al., [FPTree: A Hybrid SCM-DRAM Persistent and Concurrent B-Tree for Storage Class Memory](https://dl.acm.org/citation.cfm?id=2915251), in SIGMOD, 2016.
* S. Lee, et al., [WORT: Write Optimal Radix Tree for Persistent Memory Storage Systems](https://www.usenix.org/system/files/conference/fast17/fast17-lee.pdf), in FAST, 2017.
* J. Arulraj, et al,. [BzTree: A High-Performance Latch-free Range Index for Non-Volatile Memory](http://www.vldb.org/pvldb/vol11/p553-arulraj.pdf), in PVLDB, 2018.
* T. Wang, et al,. [Easy Lock-Free Indexing in Non-Volatile Memory](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8509270), in ICDE, 2018.
* D. Hwang, et al,. [Endurable Transient Inconsistency in Byte-Addressable Persistent B+-Tree](https://www.usenix.org/system/files/conference/fast18/fast18-hwang.pdf), in FAST, 2018.

## In-Memory Tree Indexing
* T. Lehman, et al., [A Study of Index Structures for Main Memory Database Management Systems](http://www.vldb.org/conf/1986/P294.PDF), in VLDB, 1986.
* J. Rao, et al., [Cache Conscious Indexing for Decision-Support in Main Memory](http://www.vldb.org/conf/1999/P7.pdf), in VLDB, 1999.
* J. Rao, et al., [CSB+Tree Making B+-Trees Cache Conscious in Main Memory](https://dl.acm.org/citation.cfm?id=335449), in SIGMOD, 2000.
* M. Bender, et al., [Cache-Oblivious Streaming B-Trees](https://dl.acm.org/citation.cfm?id=1248393), in SPAA, 2007.
* C. Kim, et al., [FAST: Fast Architecture Sensitive Tree Search on Modern CPUs and GPUs](https://dl.acm.org/citation.cfm?id=1807206), in SIGMOD, 2010.
* Y. Mao, et al., [Cache Craftiness for Fast Multicore Key-Value Storage](https://dl.acm.org/citation.cfm?id=2168855), in EuroSys, 2012.
* J. Levandoski, et al., [The Bw-Tree: A B-tree for New Hardware Platforms](https://www.microsoft.com/en-us/research/publication/the-bw-tree-a-b-tree-for-new-hardware/), ICDE, 2013.
* V. Leis, et al., [The Adaptive Radix Tree: ARTful Indexing for Main-Memory Databases](https://db.in.tum.de/~leis/papers/ART.pdf), in ICDE, 2013.
* V. Leis, et al., [The ART of Practical Synchronization](https://dl.acm.org/citation.cfm?id=2933352), in DaMoN, 2016.
* H. Zhang, et al., [Reducing the Storage Overhead of Main-Memory OLTP Databases with Hybrid Indexes](https://dl.acm.org/citation.cfm?id=2915222), in SIGMOD, 2016.
* R. Binna, et al., [HOT: A Height Optimized Trie Index for Main-Memory Database Systems](https://dl.acm.org/citation.cfm?id=3183713.3196896), in SIGMOD, 2018.


## In-Memory Hash Indexing
* X. Li, et al., [Algorithmic Improvements for Fast Concurrent Cuckoo Hashing](https://dl.acm.org/citation.cfm?id=2592820), in EuroSys, 2014.
* S. Richter, et al., [A Seven-Dimensional Analysis of Hashing Methods and Its Implications on Query Processing](
http://www.vldb.org/pvldb/vol9/p96-richter.pdf), in VLDB, 2015.

## NVM-Based Hash Indexing
* P. Zuo, et al., [Write-Optimized and High-Performance Hashing Index Scheme for Persistent Memory](https://www.usenix.org/system/files/osdi18-zuo.pdf), in OSDI, 2018.
* M. Nam, et al., [Write-Optimized Dynamic Hashing for Persistent Memory](https://www.usenix.org/system/files/fast19-nam.pdf), in FAST, 2019.
* B. Lu, et al,. [Scalable Hashing on Persistent Memory](http://www.vldb.org/pvldb/vol13/p1147-lu.pdf), in VLDB, 2020.

## SSD-Based Hash Indexing
* P. Jin, et al,. [SAL-Hashing: A Self-Adaptive Linear Hashing Index for SSDs](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8565887), in TKDE, 2020.

## Bitmap Indexing
* C. Chan, et al., [Bitmap Index Design and Evaluation](https://dl.acm.org/citation.cfm?id=276336), in SIGMOD, 1998.

## Approximate Indexing
* M. Athanassoulis, et al., [BF-Tree: Approximate Tree Indexing](http://www.vldb.org/pvldb/vol7/p1881-athanassoulis.pdf), in VLDB, 2014.
* T. Kraska, et al., [The Case for Learned Index Structures](https://arxiv.org/abs/1712.01208), in SIGMOD, 2018.
* H. Zhang, et al., [SuRF: Practical Range Query Filtering with Fast Succinct Tries](https://dl.acm.org/doi/pdf/10.1145/3183713.3196931), in SIGMOD, 2018.
* J. Ding, et al., [ALEX: an updatable adaptive learned index](https://dl.acm.org/doi/pdf/10.1145/3318464.3389711), in SIGMOD, 2020.
* V. Nathan, et al,. [Learning multi-dimensional indexes](https://dl.acm.org/doi/pdf/10.1145/3318464.3380579), in SIGMOD, 2020.
* C. Tang, et al,. [XIndex: A Scalable Learned Index for Multicore Data Storage](https://dl.acm.org/doi/pdf/10.1145/3332466.3374547), in, PPoPP, 2020.
- - -

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yingjun Wu](https://yingjunwu.github.io/) has waived all copyright and related or neighboring rights to this work.
