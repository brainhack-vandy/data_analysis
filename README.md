# Event Data Analysis Guide

## Data Security and Privacy Considerations

### Data Storage
- Store all data files locally and DO NOT upload raw data to GitHub or any public repository
- If version control is needed, use `.gitignore` to exclude data files
- Consider using sample data or anonymized subsets for documentation purposes

### Privacy Requirements
1. Remove entries for participants who did not consent to data usage
2. Document the process of consent verification
3. Keep a separate record of excluded entries for audit purposes
4. Maintain a log of when and why data was excluded

## Data Cleaning Protocol

### Standardizing Manual Entries
1. Review and standardize educational fields:
   - Create a mapping table for similar entries (e.g., "Computer Science" = "CS" = "CS Vanderbilt")
   - Document all equivalences in a separate reference file
   - Include original and standardized values in the cleaning log

2. Create a data cleaning log with:
   - Original value
   - Standardized value
   - Reason for change
   - Date of modification
   - Person responsible for the change

## Statistical Analysis Framework

### Demographic Analysis
1. Calculate basic statistics:
   - Age distribution
   - Gender representation
   - Geographic distribution
   - Educational background
   - Professional experience
     
2. Documentation of any assumptions made during analysis

## Reporting Guidelines

### Data Visualization
1. Include clear labels and legends
2. Note excluded categories or filtered data
3. Provide context for interpretations

## Reproducibility Checklist

- [ ] Data exclusions documented
- [ ] Manual entry standardizations logged
- [ ] Privacy requirements met
- [ ] Analysis code version controlled
- [ ] Data cleaning steps documented
- [ ] Statistical assumptions stated
- [ ] Results independently verified
