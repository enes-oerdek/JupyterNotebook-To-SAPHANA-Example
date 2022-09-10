# Jupyter Notebook to SAP HANA Example
This repository provides an easy to use example for how to connect and persist data to SAP HANA within a Jupyter Notebook. It uses the existing "to_sql" interface of DataFrames and makes easy persistence possible.

##Sample Data
The sample data comes from the [Mannheim OpenData Tool](https://mannheim.opendatasoft.com/explore/dataset/bevolkerungsbestand-in-mannheim-2009-2020/information/?disjunctive.gemeindeteilschlussel&disjunctive.gemeindeteilname&sort=-id). The dataset is licensed under [dl-de/by-2-0](https://www.govdata.de/dl-de/by-2-0).

## Dependencies
* pandas
* numpy
* hdbcli
* sqlalchemy

You can simply use pip to install the dependencies. Example:

`
pip install hdbcli
`

## Quickstart
It is as simple as it looks. Just add your credentials into the Notebook's according variables, run it and see your persisted data in your SAP HANA instance.

## Further Information
I documented more information about this repository and it's use case in my blog. [You can find the according blogpost here](https://enesordek.com/?p=2502) (in german).
