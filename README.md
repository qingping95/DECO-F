# DECO-F

Dataset released from paper "Numerical Formula Recognition from Tables" (KDD 2021)

@inbook{10.1145/3447548.3467425,
  author = {Yang, Qingping and Cao, Yixuan and Li, Hongwei and Luo, Ping},
  title = {Numerical Formula Recognition from Tables},
  year = {2021},
  isbn = {9781450383325},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3447548.3467425},
  abstract = {Claims over the numerical relationships among some measures are commonly expressed in tabular forms, and widely exist in the published documents on the Web. This paper introduces the problem of numerical formula recognition from tables, namely recognizing all numerical formulas inside a given table. It can well support many interesting downstream applications, such as numerical error correction in tables, formula recommendation in tables. Here, we emphasize that table is a kind of language that adopts a different linguistic paradigm from natural language. It uses visual grammar like visual layout and visual settings (e.g., indentation, font style) to express the grammatical relationships among the table cells. Understanding tables and recognizing formulas require decoding the visual grammar while simultaneously understanding the textual information. Another challenge is that formulas are complicated in terms of diverse math functions and variable-length of arguments. To address these challenges, we convert this task into a uniform framework, extracting relations of table cell pairs in a table. A two-channel neural network model TaFor is proposed to embed both the textual and visual features for a table cell. Our framework achieves the formula-level F1-score = 0.90 on a real-world dataset of 190179 tables while a retrieval-based method achieves F1-score = 0.72. We also perform extensive experiments to demonstrate the effectiveness of each component in our model, and conduct a case study to discuss the limits of the proposed model. With our published data this study also aims to attract the community's interest in deep semantic understanding over tables.},
  booktitle = {Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery &amp; Data Mining},
  pages = {1986–1996},
  numpages = {11}
}
