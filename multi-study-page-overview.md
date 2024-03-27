---
description: >-
  Multi-study analysis is an advanced tool designed for analyzing and
  visualizing multiple RNA sequencing studies concurrently.
---

# Multi-study Page Overview

#### Selecting studies for Multi-study analysis: <a href="#adcagqrqpdky" id="adcagqrqpdky"></a>

* The multi-study page is used to initialize the parameters for data visualization of the multiple studies. Researchers can uncover intricate patterns of gene expression associated with specific conditions or treatments across a variety of experiments. Below are detailed instructions on how to effectively navigate and utilize the Multi-Study Page.
  * For your initial test, let's use rodent studies as an example.
  * Start by selecting "rodent" as the organism of interest. Since combining DNA microarray assays is not supported, ensure filtering by both "rodent" and "RNA sequencing" in the assay technology type.
  * Choose two different rodent studies that encompass various tissue types. For instance, select "OSD-49" and "OSD-100."
  * Mark the checkboxes beside the selected studies in the studies table.
  * Click the "Visualize Study" button to proceed.
  * In this example OSD-49 & OSD100 have been selected, normalized with DESeq2 and their first 2 principle components plotted in a 2D scatter plot. To the right the is a factor selection tab where you can add new factors that will appear as columns beside the OSD-###. Clicking on the “Expand table” button reveals a table showing all the replicates and the metadata the user loads.

<figure><img src=".gitbook/assets/image (9).png" alt="Screenshot showing the graphical user interface of the Multi-study visualization application showing data for OSD-49 &#x26; OSD-100."><figcaption><p><em>Screenshot showing the graphical user interface of the Multi-study visualization application showing data for OSD-49 &#x26; OSD-100.</em></p></figcaption></figure>

#### Multi-study Data Normalization: <a href="#n1ennvxv3ysp" id="n1ennvxv3ysp"></a>

**A dialogue box will appear to prompt you for data normalization options.** The default selection is often "DESeq2" for normalization, but you can also choose "No Normalization."

* **E-mail notification:** If desired, you can enter your email address to receive a notification when the studies have been combined and normalized. Alternatively, proceed without entering an email address.
* **Normalization and PCA Insights:** Understand normalization details by clicking the Information button next to the normalization method. View the PCA chart, which provides insights into data distribution after normalization.
* **Factor Selection and Differential Gene Analysis:** Under "Factor Selection," choose variables to generate a factors table for differential gene analysis. Select parameters, characteristics, or factors from the dropdown list to add to the table.
* **Exploring the Multi-Study Page:** A PCA chart for data visualization will be included on the multi-study page. Utilize the PCA chart options to tailor your visualization based on specific criteria.
* **Modifying Normalization Method:** If you wish to change the normalization method (e.g., from "DESeq2" to "No Normalization"), click "Change Normalization Method."
* **Sample Selection for Gene Expression Analysis:** Select specific samples by clicking the "Select labelled, expand table" button. Choose samples based on factors added during factor selection.
* **Visualizing and Downloading Results:** Click "Visualize Studies" to proceed to visualization plots or download the accounts table. Depending on your selection, enter your email address for a notification upon completion.
* **Exploring Visualization Plots:** Upon completion, the page will direct you to a range of visualization plots and graphs for your data analysis.

[Link to the detailed tutorial can be found here](https://genelab.nasa.gov/sites/default/files/2024-03/Data%20Visualization%20Portal%20JT\_AU.pdf) or viewed below.

{% embed url="https://genelab.nasa.gov/sites/default/files/2024-03/Data%20Visualization%20Portal%20JT_AU.pdf" %}



#### &#x20;<a href="#adcagqrqpdky" id="adcagqrqpdky"></a>

#### &#x20;<a href="#n1ennvxv3ysp" id="n1ennvxv3ysp"></a>
