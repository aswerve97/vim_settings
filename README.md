# vim_settings

# Windows 10 Specific Information 

You must add the folder to where the VIM executable is to the system path variable. 
So run the following commands 

```
$Env:Path += ";C:\Program Files (x86)\Vim\vim90"
$profile 
vim whatevertheoutputoflineoneis
enter insert mode and then paste the following $Env:Path += ";C:\Program Files (x86)\Vim\vim90"
```

