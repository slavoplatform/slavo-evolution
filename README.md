# slavo-evolution

This repository contains all information about Slavo evolution and development.

If you like to contribute, feel free to create issues and propose changes using pull requests.

## What is Slavo?

Slavo is an extensible execution platform and associated programming language. It is designed to create safe execution environments exposing only selected resources in a controlled manner. This means that it allows you to build programmable resources available online. Minimum Slavo platform allows only single-threaded code execution with access to standard input and output of the host operating system. Each additional function, such as access to the file system, spawning threads, accessing network, or even custom hardware access, is provided by native platform extensions.

## Platform

It is a key element of this project. Its modularity allows building tailored execution environments for all types of needs. Since almost all functions allowing to interact with host operating system (or maybe in future also bare metal IoT devices) are provided by extensions. This means that if you need to access only one file from a file system, you can provide an extension that does not allow to access any other files at all. It also allows us to build dedicated functions that can communicate with custom hardware solutions.

## Language

Slavo language is an integral part of the project. It is meant to be executed on the provided platform as dynamically typed, interpreted language. It is functional language with extensive pattern matching usage, allowing to build safe code without actual types. Its dynamism also allows benefiting from the modularity of the execution environment more easily.
