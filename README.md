# Collective Classification Models For Data Without Explicit Linkage

This code base is a part of "Collective Classification Models For Data Without Explicit Linkage" paper, currently under peer-review for CODS-COMAD 2023.

## Install Dependencies

To install dependencies copy the commands below and paste in your conda prompt to install in your local conda environment.

    pip install numpy==1.21.2
    pip install pandas==1.3.5
    pip install networkx==2.6.3
    pip install sklearn==1.0.2
    pip install re==2.2.1
    pip install nltk==3.6.7
    pip install clean-text==0.5.0
    pip install csv==1.0

**Note:** If you are using a Jupyter/Colab notebook, add '!' before every pip install command and run it in a cell. For example, '!pip install clean-text==0.5.0'.

## Instructions

- Change all the file paths given in Preprocessing.ipynb, Models/ICA, Models/Spectral Clustering according to your local environment path. 

- Install all the dependencies mentioned above and run all the cells in Preprocessing/Preprocessing.ipynb. Running all the cells will generate edge_list.csv (Contains edge list of graph used to create graph, which is input to the models in Models/ICA and Models/Spectral Clustering), class_labels.npy (Contains ground-truth of all documents) and feature_matrix.npy (Contains feature matrix).

- Run all cells in notebooks from Models/ICA to obtain the results of Naive Bayes and ICA variants for different data distributions (Only data distribution i.e) random state value differs between ICA_notebook_1, ICA_notebook_2 etc.).

- Run all cells in notebook from Models/Spectral Clustering to obtain the results of Spectral Clustering.

## Citation

[1]: François Rousseau, Emmanouil Kiagias, and Michalis Vazirgiannis. 2015. Text Categorization as a
Graph Classification Problem. In Proceedings of the 53rd Annual Meeting of the Association for
Computational Linguistics and the 7th International Joint Conference on Natural Language
Processing (Volume 1: Long Papers), pages 1702–1712, Beijing, China. Association for
Computational Linguistics.

[2]: Noushin Rezapour Asheghi, Katja Markert, and Serge Sharoff. 2014. Semi-supervised Graph-based
Genre Classification for Web Pages. In Proceedings of TextGraphs-9: the workshop on Graph-based
Methods for Natural Language Processing, pages 39–47, Doha, Qatar. Association for
Computational Linguistics.

[3]: Perozzi, B., Al-Rfou, R. & Skiena, S. (2014) Deepwalk: online learning of social representations.
International Conference on Knowledge Discovery and Data Mining. New York, NY, USA:
Association for Computing Machinery.

[4]: Namata, Galileo & Kok, Stanley & Getoor, Lise. (2011). Collective Graph Identification. Proceedings
of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 10. 87-95.
10.1145/2020408.2020429.

[5]: Namata, Galileo & Kok, Stanley & Getoor, Lise. (2011). Collective Graph Identification. Proceedings
of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 10. 87-95.
10.1145/2020408.2020429.

[6]: Mahmood, Arif & Mian, Ajmal & Owens, Robyn. (2014). Semi-supervised Spectral Clustering for
Image Set Classification. Proceedings of the IEEE Computer Society Conference on Computer
Vision and Pattern Recognition. 10.1109/CVPR.2014.23.

[7]: Li, Jia & Rong, Yu & Cheng, Hong & Meng, Helen & Huang, Wenbing & Huang, Junzhou. (2019).
Semi-Supervised Graph Classification: A Hierarchical Graph Perspective ACM Reference Format.
10.1145/3308558.3313461.

[8]: Narayanan, Annamalai & Mahinthan, Chandramohan & Venkatesan, Rajasekar & Chen, Lihui & Liu,
Yang & Jaiswal, Shantanu. (2017). graph2vec: Learning Distributed Representations of Graphs.

[9]: F. Lin and W. Cohen. Semi-supervised classification of network data using very few labels. In
Advances in Social Networks Analysis and Mining (ASONAM), 2010 International Conference on,
pages 192–199, Aug 2010.

[10]:  http://groups.di.unipi.it/~gulli/AG_corpus_of_news_articles.html - AG Corpus News Articles Dataset

[11]: https://github.com/Prasath2001/Graphical-Network-Models-for-Document-Classification - Code Base

## Contact

For any queries, contact [prasath.murugesan2001@gmail.com](mailto:prasath.murugesan2001@gmail.com) & [shamtcs@gmail.com](mailto:shamtcs@gmail.com).


