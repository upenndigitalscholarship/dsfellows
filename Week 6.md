#Week 6

##OpenRefine
- What is OpenRefine
- How is OpenRefine useful
- How is OpenRefine useful to Digital Scholarship, and how does it define data?

##OpenRefine Tutorial
- Useful link: http://enipedia.tudelft.nl/wiki/OpenRefine_Tutorial

## What you will need
- [OpenRefine] (http://openrefine.org)
- [Monument Lab CSV file] (https://www.opendataphilly.org/organization/monument-lab)

Open refine is a good way to:
- Clean data
- Sort data

What is a CSV file?
- CSV stands for Comma-Separated Values
- Allows individual data inputs that are separated by commas to be saved as structured tables.
- Can make a CSV file using Excel, Word, Google Spreadsheets
- Can use OpenRefine (formerly Google Refine) to parse through the data


### Ex. 1 Sorting Data
- What: Use OpenRefine to filter and sort through data
- Show Text filter- filtering through data points manually
- How to use a text Facet
  - Type in "street"
  - All the data points with the word "street" should appear
- How to use a numerical facet
  - Type in "1"
  - All the data points with number "1" will appear


### Ex. 2 Cleaning Data
- What: Clean and make data entries consistent

- Show: Address -> Facet (Should see names of addresses input by people)
  - What are the inaccuracies here?
  - "Center City" (3) and "Center City" (1) -- why are there so many duplicate entries?
    - Spelling errors and input errors

  - Mixed inputs-- how to Transform data
    - Age --> Text Facet --> "Old"
    - Let's give "old" a numeric value e.g. 0
    - Age --> Edit cells --> Transform
    - value.replace("old", "0")
    - All the "old" entries should now be under "0"
