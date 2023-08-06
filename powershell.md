# convert unix time to time
```
Get-Date -UFormat %s
```
```
(Get-Date 01.01.1970)+([System.TimeSpan]::FromSeconds(1691250430.70317))
```
```
(Get-Date 01.01.1970).AddSeconds(1691250430.70317)
```