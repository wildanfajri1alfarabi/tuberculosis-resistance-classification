# tuberculosis-resistance-classification
 Python based pipeline for classifying Mycobacterium Tuberculosis first-line drugs resistance from DNA genome sequence powered by ML model

# Tools
Tools/library used in the pipeline :
- Tabula : Extracting DST data from pdf files into csv
- enaWebTools (FTP) : https://github.com/enasequence/enaBrowserTools
- ARIBA : https://github.com/sanger-pathogens/ariba <br>
- scikit-learn : https://github.com/scikit-learn/scikit-learn
- TensorFlow : https://github.com/tensorflow/tensorflow

# Flowchart
<p align="center">
<img src="/img/flowchart_skripsi.png" width="480" title="pipeline flowchart">
</p>

# Current Progress 
Goals need to be achieved :
- Change File Transfer Protocol (FTP) to Fast and Secure Protocol (FASP) for using ASPERA on enaWebTools. Because the bandwidth is limited if using FTP for downloading the sequence FASTQ.
- Feature engineering of report.tsv from ARIBA run function as a input to train RF model classifier.
- Modify RF and DT classifier into MLRF.
