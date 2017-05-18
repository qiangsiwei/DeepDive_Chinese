DeepDive for Chinese
==========

To change the stanford parser for Chinese, please copy parser dir to udf/bazaar/.

Then, download stanford-srparser-2014-10-23-models.jar and stanford-chinese-corenlp-2016-01-19-models.jar from stanford NLP website and put them under udf/bazzar/parser/lib/.

Then, under udf/bazzar/parser/, please run "sbt/sbt stage" to rebuild the project.

To test out, you can run "./run.sh -p 8080", and POST anything to port 8080 to see the result.

![Alt Text](https://raw.githubusercontent.com/qiangsiwei/DeepDive_Chinese/master/test.png)


