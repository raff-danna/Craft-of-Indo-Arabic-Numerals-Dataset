# Dataset for The Craft of Indo-Arabic Numerals: How Practical Arithmetic Shaped Commerce and Mathematics in Western Europe, 1200–1600

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19829542.svg)](https://doi.org/10.5281/zenodo.19829542)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)

## Overview
This repository contains the primary research data associated with the monograph:

**Raffaele Danna, ‘The Craft of Indo-Arabic Numerals: How Practical Arithmetic Shaped Commerce and Mathematics in Western Europe, 1200–1600‘, Cambridge (Mass): Harvard University Press, 2026**  
ISBN: 978-0-674-27933-9  
(https://www.hup.harvard.edu/books/9780674279339)

## Project Summary
The dataset provides evidence on the European tradition of practical mathematics, covering manuals of practical arithmetic written in western Europe from the late 13th century to 1600.

## Methodology & Sources
The evidence was gathered from existing catalogues, from specialised studies, and from archival research. For more details, see: 

- The ‘Note on sources’ in Raffaele Danna, ‘The Craft of Indo-Arabic Numerals: How Practical Arithmetic Shaped Commerce and Mathematics in Western Europe, 1200–1600‘, Cambridge (Mass): Harvard University Press, 2026;
- The variable 'source' in the dataset.

## File List
* `Practical_Arithmetic_web_Db`: The main dataset on practical arithmetic manuals. 
* `LICENSE`: Creative Commons Attribution-NonCommercial 4.0.
* `CITATION.cff`: Citation metadata for the repository.

## Data Dictionary (Codebook)
| Variable | Type | Description |
| :--- | :--- | :--- |
| `Year` | Integer/string | Year of composition/publication of the document. Strings: XIV: ‘14th century’; XIII_ex: ‘end of 13th century’; XIV_in: ‘beginning of 14th century’; XIV_I: ‘first quarter of 14th century’; XIV_II: ‘second quarter of 14th century’; XIV_med: ‘middle of 14th century’. |
| `Approx_date` | Binary | 1 = date is approximate; 0 = date is certain. |
| `Area` | String | Geographical area of composition of the document. |
| `City` | String | City of composition of the document. |
| `Author` | String | Name of author (‘anonymous’ when unknown). |
| `Title` | String | Title of the document. |
| `Language` | String | Language of the document. |
| `Ms.` | Binary | 1 = document is manuscript; 0 = document is printed. |
| `Printer` | String | Name of printer (empty cells for manuscript documents). |
| `External_link` | String | Link to online resource or digital reproduction. |
| `Source` | String | Bibliographic references. |
| `Location` | String | Document’s current location. |
| `Contents` | String | Contents/matters covered in document. |

**Cleaning Notes:**
* Text punctuation: Double quotes (`"`) have been converted to apostrophes (`'`) to ensure CSV compatibility.
* Delimiter: This file is comma-separated.
* Missing data is reported as an empty cell.

## How to Cite
If you use this data, please cite both the book and the dataset:

**Book:**
Danna, R., *The Craft of Indo-Arabic Numerals: How Practical Arithmetic Shaped Commerce and Mathematics in Western Europe, 1200–1600*. Cambridge, MA: Harvard University Press, 2026. ISBN: 978-0-674-27933-9

**Dataset:**
Danna, R. (2026). *Dataset for The Craft on Indo-Arabic Numerals*. Version 1.0.0. Zenodo. https://doi.org/10.5281/zenodo.19829542

## Contact
Website: [https://rafdanna.com/](https://rafdanna.com/)
