
# DAT250 - Experiment Assignment 6

## Technical Problems Encountered

During the completion of this assignment, I encountered the following technical issues:

1. Classpath Issues:
   Initially, I faced challenges with setting up the correct classpath for the RabbitMQ client and logging libraries.
   The `javac` and `java` commands were not able to locate the necessary `amqp-client` and `slf4j` dependencies, which resulted in `ClassNotFoundException` errors. 
   This issue was resolved by ensuring the classpath included the compiled class files and the necessary external JARs.
2. $CP env Issue:
   I encountered an issue with the `$CP` environment variable when running the java -cp command. The script was not able to locate the necessary JAR files, which resulted in a `.ClassNotFoundException`.
   This issue was resolved by ensuring the `$CP` environment variable was correctly set to include the necessary JAR files.

## Code for Experiments 1-4

You can find the code for experiments 1-4 at the following link:
[Repository Link](https://github.com/SindreEieLedsaak/Dat250_Messaging/tree/main/src/main/java/org/example)

## Pending Issues

I have not encountered any major issues that are still pending.