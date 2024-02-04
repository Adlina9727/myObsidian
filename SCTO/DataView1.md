---
Summary: Enter your summary for the table view here.
---
```dataview 
LIST file.ctime
```

## Primary Sources rate 5/5"
```dataview 
LIST FROM "Primary Sources" where rating = "5/5"
```
## List of activity
```dataview 
LIST FROM "Activity"
```
## List of activity during one week 

```dataview
LIST
WHERE file.mtime >= date(today) - dur(1 week)
LIMIT 5
```

## Case Study 3

```dataview 
TASK WHERE !completed
LIMIT 1
GROUP BY file.link 
SORT rows.file.ctime ASC
```

## Calendar 
```dataview
Calendar file.ctime from "Primary Sources"
```

## List of Paper 
```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM "Primary Sources" sort Rating DESC
```

## Review Paper 
```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM #reviewpaper AND "Primary Sources"  sort Rating DESC
```

## Machine Learning Paper 
```dataview
TABLE without id file.link as Paper, ShortSummary as Summary, Rating FROM #Machine_learning  AND "Primary Sources"  sort Rating DESC
```
