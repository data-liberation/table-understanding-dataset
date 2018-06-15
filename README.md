# table-understanding-dataset
table understanding dataset for  comparative evaluation of different table understanding algorithms



The problem of table understanding has attracted much interest in previous years from the database as well as the document engineering communities. On the Web, discovering structured data is a tremendous challenge and PDF documents represent the most common document format after HTML. It is commonly recognized that table understanding consists of three tasks of increasing complexity:     

* table detection: locating the regions of a document with tabular content;        

* table structure recognition: reconstructing the cellular structure of a table;          

* table interpretation: rediscovering the meaning of the tabular structure. This includes:         

  (a) functional analysis: determining the function of cells and their abstract logical relationships;       

  (b) semantic interpretation: understanding the semantics of the table in terms of the entities represented in the table, their attributes, and the mutual relationships between such entities.       




## scanned images dataset

* UW datasets:[I. T. Phillips. User's reference manual for the uw english/technical document image database III.Technical report, Seattle University, 1996]()

* UNLV:[http://www.isri.unlv.edu/ISRI/OCRtk. No longer available; accessed at web.archive.org]()   


## native pdf dataset

* PDF-TREX system:[it contains mostly Italian financial tables and does not include ground-truth information]()    

*  ICDAR 2013 Table Competition :[Ground-truthed datasets of PDF tables contains 59 excerpts as individual PDF les, with a total of 117 tables](http://www.tamirhassan.com/dataset.html)
>EU-data set and the US-data set. The EU-data set currently consists of 34 public domain documents, gathered from various European
Union government websites. The US-data set consists of 25 public domain United States government website PDF documents. Both data sets contain an eclectic set of tables, that for the most part surpass the typical scientific publication table complexities by a large margin (see Chapter 3.2). The test data ground truth table areas exclude both the table title and legend. The table detection algorithm had to be modified to accommodate these changes for the testing phase.
The two used data sets (EU and US) sets are a part of an International Conference on Document Analysis and Recognition (ICDAR) 2013 table competition* and they are freely available on the Internet [13]. The data sets are likely to be expanded in the future,while the authors of Göbel et al. [14] are working towards a more unified toolkit for standardized testing methods for table detection and structure recognition. The ground truths for the data sets are provided by Göbel et al. [14]. 


* Data to evaluate our extractor was gathered from a variety of computer science conferences and then hand annotated. In total 150 papers were annotated, resulting in 458 figures and 190 tables. Bounding regions for figures, tables, and captions were identified using LabelMe and post processed to get cropped bounding squares.:[DATASET](https://www.dropbox.com/s/ydr3asu406hl4ho/dataset.tar.gz?dl=0)
[Visualization of Ground Truth Annotations ](https://www.dropbox.com/sh/hfqa6mn6pznczex/AAA_MuCm3XBPs5AOLTXFLqY_a?dl=0)

* [Page Object Detection(POD) is to detect the specific page objects(e.g. tables, formulas, figures(including charts)) in document images. The dataset contains more than 2000 images with various kinds of page objects. Participants are required to detect these page objects in the provided dataset. ](http://www.icst.pku.edu.cn/cpdp/ICDAR2017_PODCompetition/results.html)
