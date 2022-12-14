# Copy and Download

</br>

**Copy and Download** is the most simple data sharing approach where the _data controller_ shares copies of data directly with other parties, the _data recipients_. This approach is the easy to implement and is still being used the most, but comes with a number of drawbacks.

```{figure} ./_static/img/datastrategy1.png
---
height: 464px
name: datastrategy1
---
```

The most simple form of Copy and Download is by sending data files, such as excel files or compressed archives, via email or via a public download link. More advanced and secure methods are for example by creating Application Programming Interfaces [(API)](https://www.hl7.org/fhir/http.html) that control access to the data, through a secure or private download link. 

In most cases the _data controller_ and _data recipient_ make a legal agreement in which the limitations of further data usage are being described. Still, Copy and Download poses the problem of losing control over the spread of data, does not impose limitations on resharing or copying of data and does not inherently provide means of tracking data access. This can raise privacy concerns and makes the method unsuitable when dealing with sensitive data. 

Furthermore, Copy and Download works for single projects on the receivers end. Changes made on the data locally prove hard to merge with the remote data state. This poses serious challenges when working with multiple parties on the same data,  since everybody needs to make sure they have the valid (often most recent) version of the data. 

Another problem can be that the data recipient needs to have proper expertise on how to process the data. In some cases, certainly if a data exchange process needs to be automated, standardization according to the appropriate ontologies is necessary although in other cases exchange of a simple text files might be the most straight forward way for data exchange. 

 </br>

:::{seealso}

*Bringing Code to Data: Do Not Forget Governance*, article available on [PubMed](https://pubmed.ncbi.nlm.nih.gov/32540846/).

:::
