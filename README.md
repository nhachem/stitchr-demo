# stitchr-demo-data
This holds a generated dataset from tpcds.

download and unzip the data file. under data/tpcds
gunzip *.gz
adjust the env.sh file parameter DEMO_DATA to point to the data folder

  source the env.sh

to run the demo

  spark-shell --jars $STITCHR_ROOT/core/target/stitchr-core-0.1-SNAPSHOT-jar-with-dependencies.jar

then load and run the DemoBasicStitchr.scala script

  :load <path-to-where-stitchris-deployed>/stitchr/core/scripts/demo.scala
