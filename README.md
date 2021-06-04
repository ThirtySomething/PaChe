# PaChe

 Checks environment variable PATH on MS Windows

## Motivation

As a curious user, I install and remove a lot of programs. Some of them do not remove their paths from the PATH variable. Many non-existent directories inflate the PATH variable unnecessarily.

## Solution

This script reads the PATH variable, splits it into its components and checks the existence of each directory.
