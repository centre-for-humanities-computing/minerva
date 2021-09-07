# sep 7 2021

## Access
- Tom owns domain itiner-e.org
- additional access permissions assigned by project owners
  - read and maintain permissions
- private site

## Data Upload
- rare (on completed sections)
- shape files -> json (https://github.com/calvinmetcalf/shapefile-js)
- max 10000 rows (~20MB)
- github repo for syncing, they upload, we push, they are collaborators

- sqlite
- postgre has plugin for shapefile (ask Pau)

no editing online before 2023!

## Data Model
persistent ids (after upload)
with semantic attributes
section data | semantic data
user
    first and last name
    email
    passphrase

later: editor id

## Visualisation
d3.js 

select for export
    not urgent, relevant at end of project (2yrs)
    select polygon: everything touched will be exported
    select attributes to export
    csv or klm or shapefile

## use case
- search by attribute value
  - single or multiple
  - numbers in ranges (years have errors (apply on both sides))
- browse by map

__at the end of project (2023)__
- login to edit
- persistent ids
- upload as user (shapefile >> earmarked as coming from user)
- suggest edits as user
