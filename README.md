Readme file about the usage of the metadata.csv file of the Soybean Seedlings Dataset.

If you are using for academic purpose, please cite:

Bruno C. Nascimento, Marcos H. F. Ribeiro, Laércio J. Silva, Nayara Capobiango, Michel M. S. A soybean seedlings dataset for soil condition and genotype classification. 35th SIBGRAPI Conference on Graphics, Patterns and Images, 2022.

The metadata file contains the genotype and soil condition of each soybean seedling image and the division performed for training, validation and testing. They are presented as a file of values separated by two points (CSV) using a semicolon (';' ) as delimiter and with a number of lines equal to the number of soybean seedlings images plus a header identifying each column.

The file has six different columns, these are detailed below:

- ‘index’: Instance index. Referring to a dataset image;
- ‘name’: Image name. The name is composed of the block, genotype and soil condition referring to the seedling represented in the image;
- ‘genotype’: Soybean genotype. There are 30 distinct genotypes, the value ranges from 0-29;
- ‘condition’: Soybean soil condition. The soil condition in which the seedling was grown, which can be compacted - 'comp' or control 'ctr';
- ‘fold’: The dataset was divided into 872 images for training and validation through 5-fold and 154 images for testing. This column indicates which fold the instance belongs to or whether it belongs to the test group.
- ‘training’: For training without the 5-fold the dataset was divided into 80% of the images for training and 20% for testing. The column indicates whether the image was used for training or testing.

Thanks for using.

