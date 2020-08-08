# Using Apache Spark Neural Networks to Recognise Digits
This library is based on the implementation of artificial neural networks in https://reorchestrate.com/posts/using-apache-spark-neural-networks-to-recognise-digits-copy/

## Installation
### Requirements
  - Apache Spark 2.1.1 or higher
  - Java and Scala
  - Maven

### Build 
Compile:
```
mvn clean install
```
The jar library will be available in `target` folder. After compiling, a ready-to-go example of use is provided before.

#### Classification
```
spark-submit --class scaladl.Classifier target/scaladl-1.0.0.jar
```