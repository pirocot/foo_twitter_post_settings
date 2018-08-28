## default


```
#nowplaying $cut(%title%,30)$if([%artist%], - $cut(%artist%,30))$if([%album%], - $char(91)$cut(%album%,30)$if([%tracknumber%], No.%tracknumber%)$char(93))
```

## current
```
♬%title% - $if2(%artist%, ) / $if2([%album%],$directory(%_path%,1)) [%date%]
```
