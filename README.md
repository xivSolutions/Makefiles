Example Makefiles
=================

Examples and Templates for Using the Make Utility with C. 

The examples in this repo are discissed in a blog post at XXXX

Simple Example
==============

The most basic example for compiling a silly hello world application. 

App-Specific Example
====================

A basic template to use for creating makefiles for your specfic applciation(s). Simply swap your application name where `TARGET` is assigned the value `hello` in the example.

Require Target Name Example
===========================

A special case for setting up a general makefile for use with varying single-file projects. 


All of the examples are based upon setting up compilation for excercises using several common commpiler flags, and (in the example case) the harvard cs50 library as an external include. This is for illustration only, and you will likely want to remove the cs50 include and/or specify your own (one or many). 
