# Genomic Change Point Detection

This repository contains a Jupyter Notebook focused on processing genomic log-ratio data and detecting change points. It provides tools for filtering, organizing, and analyzing genomic data with efficient handling of anomalies and annotations.

This a project part of the phD course on Multiple Change-Point Detection.

Made by Erica Luciani, Loris Cino, and Simone Di Gregorio

## Table of Contents
- [Overview](#overview)
- [Structure](#structure)

## Overview
The main functionalities provided in this repository include:
- Extracting log-ratio data from a pandas DataFrame using the `LogRatioExtractor` class.
- Grouping data by chromosomes or profiles.
- Handling anomalies and filtering based on annotations.
- Evaluating predicted change points against true change points.

## Structure
*LogRatioExtractor*: A class designed to extract and process log-ratio arrays grouped by specific criteria. Handles anomaly filtering, annotation filtering, and data grouping.
*filter_changepoints*: A function for filtering change points based on chromosome boundaries with specified tolerance.
*calculate_performance*: A function to evaluate prediction results, providing counts of true positives, false positives, false negatives, and true negatives.
