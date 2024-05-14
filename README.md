---
datapackage:
  title: Top 1000 universities in the world
  description: In this project, the ranking of the top 1000 universities in the world has been reviewed and analyzed.
  licenses:
  - path: https://www.apache.org/licenses/LICENSE-2.0
    title: Apache 2.0
  resources:
  - format: csv
    name: vix-daily
    path: data/vix-daily.csv
    schema:
      fields:
      - format: any
        name: Date
        type: date
      - format: default
        name: VIX Open
        type: number
      - format: default
        name: VIX High
        type: number
      - format: default
        name: VIX Low
        type: number
      - format: default
        name: VIX Close
        type: number
      missingValues:
      - ''
    title: VIX Daily
  sources:
  - path: https://www.kaggle.com/datasets/zahrayazdani81/univercitiesranking?resource=download
    title: Universities Ranking
---


# Analyzing the Dataset of the Top 1000 Global Universities

In this project, the ranking of the top 1000 universities in the world has been reviewed and analyzed.
The current project, within the framework of a scientific and research exercise in the field of machine learning, which was held in the summer of 1402 under the supervision of professor Mohammad Reza Momeni and under the guidance of mentor Amirreza Lotfi, in this exercise, the study and analysis of data related to university rankings We have discussed the effective factors.

This exercise, with the aim of cleaning the data and better understanding of the existing patterns, has been a fundamental step towards a deeper understanding of the available data in the field of machine learning.

The current dataset contains 1000 rows and 12 columns, which contains a variety of university information maps, including their names and geographic locations, scores, and various rankings.

This initial analysis reveals a dynamic and complex field of data, providing an accurate representation of the complexity and diversity of universities and guiding us in the next sections.
