# Streaming data sets

This repository contains a collection of datasets. While some data sets are used for batch learning they can be also be used in the streaming setting. On the other hand, some data sets have characteristics that make them better suited for the stream learning setting, e.g., they contain non-stationary data.

*  **Covertype Dataset** (covtype.csv)

   Type: Multi-class classification
   > Blackard, Jock A. and Denis J. Dean. 2000. "Comparative Accuracies of Artificial Neural Networks and Discriminant Analysis in Predicting Forest Cover Types from Cartographic Variables." Computers and Electronics in Agriculture 24(3):131-151.

* **Electricity Market Dataset** (elec.csv)

  Type: Binary classification
  > M. Harries, N.S. Wales, Splice-2 comparative evaluation: Electricity pricing, 1999.

* **Moving Squares Dataset** (moving_squares.csv)

  Type: Multi-class classification
  > Losing, V., Hammer, B. and Wersing, H., 2016, December. Knn classifier with self adjusting memory for heterogeneous concept drift. In Data Mining (ICDM), 2016 IEEE 16th International Conference on (pp. 291-300). IEEE.

* **Music Dataset** (music.csv)

  Type: Multi-label classification
  > Read, J., Reutemann, P., Pfahringer, B. and Holmes, G., 2016. Meka: a multi-label/multi-target extension to weka. The Journal of Machine Learning Research, 17(1), pp.667-671.

* **Weather Dataset** (weather.csv)

  Type: Binary classification

  > R. Elwell, R. Polikar, "Incremental learning of concept drift in nonstationary environments", IEEE Transactions on Neural Networks, vol. 22, no. 10, pp. 1517-1531, Oct 2011.

---

## Deprecated

SEA datasets (sea_big.csv, sea_stream.csv) were created using the `SEAGenerator`. The recommended approach is to use the `SEAGenerator` directly.
