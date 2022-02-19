# Anomalous Human Motion DataBase (AHMDB)

This is GitHub repository to store compilation of videos, namely AHMDB, as used in the experiments of our CISS'22 paper ["Development of Anomalous Video Detection System using Hybrid-Features Analysis of Actions and Scene-Backgrounds Information"](https://www.edas.info/ap/ciss2022/program.html#S1569602526). There are total of 4,903 and 1,128 short clips in training and testing folder respectively, with 274 of the testing videos are categorized as anomaly. Every video has been assigned both action label and normality label onto its name. You can download this dataset by cloning the repository.

## Citation

If you use this dataset, please cite the following:

```bibtex
@INPROCEEDINGS{Kama2203:Development,
AUTHOR="Bharindra Kamanditya",
TITLE="Development of Anomalous Video Detection System using {Hybrid-Features}
Analysis of Actions and {Scene-Backgrounds} Information",
BOOKTITLE="2022 56th Annual Conference on Information Sciences and Systems (CISS)
(CISS 2022)",
ADDRESS="Princeton, USA",
DAYS=9,
MONTH=mar,
YEAR=2022,
KEYWORDS="computer vision; machine learning; video anomaly detection; graph
convolutional networks",
ABSTRACT="Detecting an anomalous event in video clips captured from a surveillance
camera is an important task, especially for security system purposes.
However, as the probability of such occurrence is very low, automatic
detection of the anomalous event is then necessary to replace the human
labor-intensive works. Researchers have developed various methods to solve
this problem, however, most of the proposed methods limit their definitions
of anomalous events that might be perceived as having a different meaning
when it occurs in other scene backgrounds. We have developed an automatic
anomalous video detection system by extracting the individual action from
the video clips, followed by extracting also various scene-background
characteristics related with the respective action, and represented as a
Video Graph to be classified as an anomaly through a Graph Convolutional
Networks. We also constructed a new database as the available databases
could not be used in this experiment. Results of experiments show that the
various anomalous actions videos have been successfully detected with
higher recognition capability compared with that of the conventional
methods."
}
```
