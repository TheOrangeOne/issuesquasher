# issuesquasher
create sessions in which you get something done

# building

to build once
```$ lein chromebuild once```

to build on file-change

```$ lein chromebuild auto```


# development

## running in chrom*

1) run the build command then open up the browser and navigate to `chrome://extensions`

2) ensure `Developer mode` is checked and then click `Load unpacked extension...`

3) choose the `target` directory created by the build command in the root of the project directory
