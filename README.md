# Java-word-count-beam
Testing Word Count using Apache Beam

I tested the program using Maven command and also ran the program. Hence multiple output files were generated from both the cases.

Below is the Maven command I used on WordCount.java and it generated output files prefixed with "counts". Input taken from Sample.txt.

mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner




And I ran the program by taking default existing Link in Java Program gs://apache-beam-samples/shakespeare/kinglear.txt. The output will be prefixed with "wordCount".

And I also ran MinimalWordCount for better understanding of the WordCount program. These output files are prefixed with "wordcounts"
