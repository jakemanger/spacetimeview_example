# spacetimeview example

A simple example repository to show how to plot and deploy your data with `spacetimeview`.

**Install** `spacetimeview` with 

```R
install.packages('spacetimeview')
```
or 
```R
devtools::install_github('jakemanger/spacetimeview').
```

To **plot**, run `source('plot.R')`.

To **deploy** your plot to github pages, run `source('deploy.R')`. You should then be able to view your freshly deployed website at 
the url provided, e.g. https://jakemanger.github.io/spacetimeview_example/ in the below code output:

```R
> source('deploy.R')
Auto-detected time column: `DateTime`
[1] "Converting character column `timestamp` to factor"
[1] "Starting ReactR plot"
✔ GitHub Pages is publishing from:
• URL: "https://jakemanger.github.io/spacetimeview_example/"
• Branch: "main"
• Path: "/docs"
```

See [spacetimeview](https://github.com/jakemanger/spacetimeview) for more more information on how to use `spacetimeview`.

## Fork this repository for your example

If you would like to fork this repository for your example, hit the fork button at the top of this github page and make your modifications.
![image](https://github.com/user-attachments/assets/80c22450-9777-4e73-ab23-11583b303336)
