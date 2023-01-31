---
title: "Getting Started with DocuScope"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: This site contains documentation for DocuScope Corpus Analysis (or DocuScope CA), as well information for those using the docuscospacy Python package.
---

{% include note.html content="If you're seeking information about other DocuScope tools (like DocuScope Write & Audit, please check the <a alt='DocuScope homepage' href='https://www.cmu.edu/dietrich/english/research-and-publications/docuscope.html'>DocuScope homepage</a>. If you're interested in reading more about how to apply DocuScope in research, see <a href='https://benjamins.com/catalog/scl'>Corpora and Rhetorically Informed Text Analysis: The Diverse Applications of DocuScope</a>, which is scheduled to be published by John Benjamins in 2023 as part of their their Studies in Corpus Linguistics series." %}

<a>&#128736;</a> This page is currently under construction.

## Load a Corpus

The first step in using DocuScope CA is to load a corpus of plain text files.

If you're not familiar with the basics of corpus building and file preparation, see these guidelines.

Otherwise, follow these steps.

### 1. Upload files

First, select the **load corpus** tab on the left side of the window.

Scroll down to the bottom of the page, where you will find the **browse files** button. Select it.

{% include image.html file="getting_started/image8.png" caption="The widget for browsing and selecting files." %}

A dialogue window will open. Navigate to your corpus files and select them. You can select multiple files by holding down the shift key or the command key. You can also use **select all** if you have organized them in their own directory.

{% include image.html file="getting_started/image23.png" caption="A dialogue window for selecting files." %}

Alternatively, you can simply drag and drop your corpus files into the uploader.

{% include warning.html content="The uploader allows only files formatted as plain text (TXT). If you're not sure how to create plain text files, consult the guidelines for preparing a corpus. Also, the uploader limits the size of files to 200 MB. Even long novels are typically under 1.5 MB, so the size restriction shouldn't generally cause problems. But be aware if you are harvesting data from sites like Kaggle, where data has sometimes been aggregated into large files." %}

### 2. Choose a dictionary

From the drop-down menu, select the dictionary you would like to use to tag the corpus. The "dictionaries" are actually models that have been trained on different tagsets.

**Part-of-speech tagging is the same for all models. But the models are trained on different DocuScope tagsets.**

Broadly, the models are differentiated by their number of DocuScope categories:

* Large Dictionary = many categories
* Medium Dictionary = some categories
* Common Dictionary = fewer categories

Your choice of model largely depends on your data and your research questions. More categories means greater coverage (fewer tokens left "Untagged"), but also more variables with finer grained distinctions.

For more informtion, consult the DocuScope tagset descriptions.

### 3. Process a corpus

Once you have selected your desired files, they will appear in the widget. Make sure you select the "process corpus" button below the widget.

{% include image.html file="getting_started/image18.png" caption="Widget showing selected files and the process button." %}

Processing time depends on the size of your corpus. A corpus with a 250,000 words should process in just a few seconds. A corpus with 2 million words will take roughly 30 seconds.


{% include links.html %}
