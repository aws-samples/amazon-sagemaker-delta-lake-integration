## SageMaker Delta Lake Integration

This repository contains Amazon SageMaker Notebook (https://aws.amazon.com/sagemaker/) samples and code that can be used to integrate SageMaker with open-source Delta Lake tables. The objectives for accessing Delta Lake from SageMaker notebooks include:

* Build hybrid ML solutions with open-source technologies
* Extract value from pre-existing Delta Lake table data
* Allow in-place data access to avoid data duplication

We provide SageMaker Studio notebooks that load and transform data stored in the Delta Lake format. We use a standard Jupyter notebook to run Apache Spark (https://spark.apache.org/) commands that natively read and write from a Delta Lake table. The open-source library named delta-spark (https://github.com/delta-io/delta) allows users to directly access this data in its native format. This library allows users to take advantage of the many API operations to apply data transformations, make schema modifications, and use time-travel or point-in-time queries to pull a particular version of the data. In our sample notebooks, we show how to use the delta-spark library to read and write Delta Lake tables and to manipulate the underlying table structure, referred to as the schema.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

