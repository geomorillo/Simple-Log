# Simple-Log by Jochen Scharr
Essential logging in one simple, robust, static, thread-safe class. No initialization, no configuration, no dependencies. Don't think, just log. 

# Introduction
A simple but robust logging class that fulfills the following requirements:

One simple, static class, easy to understand.
Works "out of the box", just include it and start logging. No initialization, no configuration necessary. No dependencies.
Simple, static methods to write a log entry.
Logs XML fragments or plain text to a file, one tag or one line per log entry.
Easy but flexible way to change file and folder where logs are written to.
Possibility to pass log severity (info, warning, error, exception).
Possibility of simple filtering by log severity.
Log exceptions recursively with all inner exceptions, data, stack trace and specific properties of some exception types.
Has very little impact on performance of the main program due to queue-and-background task approach.
Is thread-safe, i.e., several threads can log into the same file concurrently.
Automatically logs the class and method name where the log method was called from.
Exceptions occurring when writing to the log file, e.g. due to insufficient rights, get logged to event log, including log file name and current process user name. Log source is "SimpleLog".
Robust, compact and well-documented.

The rest of the documentation here https://www.codeproject.com/Tips/585796/Simple-Log
