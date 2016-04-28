#Drupal schema generator for MySQL Workbench

## Compatibility

This pluging was tested with:
 - MySQL Workbench 6.3 CE
 - Drupal 7.x and 8.x

## Installation & usage

Select and install the wb_drupal_schema.py file via  _Scripting > Install Plugin/Module_.

The Drupal schema is generated via _Tools > Catalog > Generate Drupal schema_

## Notes

- Database specific types (*_type) are added for datefields
- Set an ascii collation on varchar columns to get a varchar_ascii type for Drupal 8.x
