# Simple JSON File-Based Database in Go

## Overview

This Go project implements a lightweight, file-based NoSQL database that stores and retrieves structured data in JSON format. It supports basic CRUD (Create, Read, Update, Delete) operations using a simple directory structure to organize data collections.

## Features

* **File-based storage:** Uses the filesystem to store JSON records in a structured directory format.
* **Basic CRUD opertions:** Create/Update/Read/Delete records.
* **Thread-safe operations:** Uses mutexes to ensure safe concurrent access.
* **Logging:** Uses the lumber logging library for structured logging. 
