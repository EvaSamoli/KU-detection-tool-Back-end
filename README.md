# KU-detection-tool-Back-end

This project is the backend API implementation for a thesis project focused on detecting Knowledge Units (KUs) in Python source code files. It is an extension of an existing system originally developed to detect KUs in Java code. This version adapts and extends the existing architecture to support the Python programming language.

## What Are Knowledge Units?
Knowledge Units (KUs) are semantically meaningful code segments that encapsulate a specific functionality, concept, or logic. Detecting KUs can help in understanding, maintaining, and reusing code more effectively.

## Description
This project implements the backend API for an application designed to detect "Knowledge Units" (KU). It is built with Flask (Python) and provides endpoints for:

Managing a list of Git repositories (Add, List, Edit, Delete).
Fetching and storing commit information from repositories.
Performing analysis on code files from specific commits using a pre-trained CodeBERT model.
Monitoring the status and progress of the analysis process.
Retrieving the analysis results (detected KUs).
The backend interacts with a PostgreSQL database for data persistence and uses Git commands for cloning/updating repositories.
