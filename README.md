# 99BottlesCsharp [unsolved]
The "99 Bottles of Beer" kata with working unit tests, but without solution

## Project Setup

In general you can quickly setup a csharp unit test project by issuing the commands below, however you don't need to do this if you clone this repository. If you get errors make sure .NET Core is installed.
```sh
$ mkdir funkyName
$ cd funkyName
$ dotnet new mstest
$ dotnet watch test
```
Clone the repository as follows:

```sh
$ git clone https://github.com/3nigm4/99BottlesCsharp.git
```

The example code snippets in the book are written in Ruby. We will not translate those to C#, because we won't need them and they should be easy to read and understand. If you’re completely unfamiliar with the language here is a gentle tutorial [(Ruby in Twenty Minutes)](https://www.ruby-lang.org/en/documentation/quickstart/).

## Doing the exercise

To run the test suite, invoke the following command in the directory of your project folder.
```sh
$ dotnet watch test
```

The test suite contains one failing test, and many skipped tests. Your goal is to write code that passes all
of the tests. Follow this protocol:

* run the tests and examine the failure
* write only enough code to pass the failing test
* remove the `[Ignore]` annotation from the next test __(this simulates writing the next test)__

Repeat the above until no tests are skipped, and you’ve written code to pass each one.
Work on this task for 30 minutes. The __vast majority of folks do not finish in 30 minutes__, but it’s useful,
for later comparison purposes, to record how far you got. Even if you can’t force yourself to stop at that
point, take a break at 30 minutes and save your code.
