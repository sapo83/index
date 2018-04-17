### Remove carriage returns (^M)
```
less data.csv | tr -d $'\r'
```

### View to see if file has carriage returns (^M)
```cat -v data.csv```
