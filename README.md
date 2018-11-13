# spark-sbt.g8

A [Giter8](https://github.com/foundweekends/giter8) template for Spark SBT applications.

## Usage

1. Start the app generation wizard: `sbt new oscarvarto/spark-sbt.g8`

2. Fill out the project properties on the command line

3. Run the tests to make sure the project was generated correctly.
   `cd` into the top level project directory and then run `sbt test`.

4. (optional) run the shell scripts to add the log4j.properties file and additional options to the
   `build.sbt` file

![giter8 gif](giter8.gif "giter8 Screenshot")

## Project Properties

**name (default: my-cool-project)**

The project name.  This should be all lowercase and use hyphens.

**package (default: com.github.mrpowers.my.cool.project)**

The top-level package of the project.  This is typically the organization name followed by the project name.

For example, the [top level package of spark-daria](https://github.com/MrPowers/spark-daria/blob/master/src/main/scala/com/github/mrpowers/spark/daria/sql/ColumnExt.scala#L1) is `com.github.mrpowers.spark.daria.sql`, which consists of the organization name `com.github.mrpowers` and the project name `spark.daria.sql`.

**scalaVersion (default: 2.11.12)**

**sparkVersion (default: 2.3.0)**

**sbtVersion (default: 0.13.17)**

**version (default: 0.0.1)**

The project version.  `0.0.1` is usually the best place to start.

## Contribution

Send pull requests to keep this project updated.

We'll always try to keep this updated with the latest version of Spark and Scala.

