# DICOM_Anonymization

Anonymizing DICOM, HIPPA Standard (knee MRI)

In this exercise we are learning how to anonymize DICOM series. It is very important to understand what is involved in anonymization and how it is done if we are planning to do any research projects with real clnical data. Either we will need to agree with the data owner on what the anonymization protocol is, or we will be dealing with data that passed such protocol. As always, understanding our data helps us build better machine learning algorithms.

The task for this exercise is to imagine that we are starting a joint research project with a hospital and they have given us a sample image series to agree on anonymiaztion protocol for their data. We will need to come up with one before we see any further data.

In this notebook we learn how to perform the actual de-identification of DICOM metadata.
We need to keep in mind that anonymization process is always a balance between reducing chances of re-identification to a reasonable minimum and keeping the dataset useful for our research purposes.
