# Software-Security-Seminar

### This is the repository for COMP63342 Software Security Seminar by Zhaoyu Zhang.

# Understanding Programming Bugs in Java Programs Using Counterexamples - Optimizing minimal counterexamples

## Dependencies
Java PathFinder(JPF)

Java Bounded Model Checker(JBMC)

IDEA Intellij Community Edition

## How to install
JPF and JBMC are required to install on your machine prior to clone this repository, please go to their github page for more details.

## How to build
Once the repository is cloned, use Intellij or terminal to build under gradle environment:

<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>./gradlew build</h1>
  </div>
</div>

and run all tests by

<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>./gradlew test</h1>
  </div>
</div>

## How to run
Run the following command:

<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>java -jar [your RunJPF.jar path] [your example.jpf built]</h1>
  </div>
</div>

An example of running can be shown as

<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>java -jar build/RunJPF.jar src/examples/Racer.jpf</h1>
  </div>
</div>

For JBMC, simply add jbmc.exe into your PATH variable(under Windows machine) and use the command in a terminal


<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>jbmc [your java '.class' file path]</h1>
  </div>
</div>

An example of running can be shown as (do not include .class suffix in argument)

<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h4>jbmc src/main/java/Testing/Main</h1>
  </div>
</div>

## Example

An example of JPF output:

![image screenshot1](./screenshot1.png)
![image screenshot2](./screenshot2.png)

## Demostration
The detailed demonstration of this seminar can be seen inside the PDF or PPT attached.
