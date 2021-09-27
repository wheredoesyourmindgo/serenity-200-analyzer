# 200-analyzer

![analyzer](https://i.ibb.co/hVkBDZd/Screenshot-from-2021-09-27-18-17-43.png)

### Commands

`Usage: ./a200 [command] [args]`

#### tc | toggle column
change the visibility of column(s) or set(s) of columns. Use `all` to toggle all columns

#### tl | toggle layout
change the visibility of layout(s)

#### st | sort
order the results based on sort parameters. Parameters can be specified as either `(-)parameter` or `(-)x%parameter`, where a negative denotes sorting from low to high instead of high to low, and x denotes the percent weight of a given metric. If the weight of some parameters are unspecified, the weight will be divided equally among them

#### tb | thumb
change which type of thumb to press space with. `LT` and `RT` represent the left and right thumb, respectively. `NONE` will throw away all trigram data with space. `AVG` will take the average of the metrics from left and right. 

#### dt | data
set the data to use in the analysis

#### tm | theme
set the color theme

#### reset
set the config to its default factory state

## Demo

a short ![demo](https://youtu.be/eeS1HR6MgEE) of the command usage
