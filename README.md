# Drupal schema generator for MySQL Workbench

## Compatibility

This pluging was tested with:
 - MySQL Workbench 6.3 CE
 - Drupal 7.x and 8.x

## Installation

Select and install the wb_drupal_schema.py file via  _Scripting > Install Plugin/Module_.

## Usage

The Drupal schema is generated via _Tools > Catalog > Generate Drupal schema_

To get the varchar_ascii type for Drupal 8, you must set an ASCII collation on the varchar column.
