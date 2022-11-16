# Learn-bootstrap
## Complete Bootstrap

> History of bootstrap

1. It is a FrontEnd Framework
2. for building responsive site 
3. original Name ```Twitter Blueprint```

## Made up of 3 thing 
- grid (for responsive)
- classes (given to html element to style it)
- Component(Pre-build html css element)
- Official Document for reference  
- documentation is known as notes

# grid System 

- make responsive
- interface remain same

## Include Bootstrap 
- CDN
- Download and attach

## Responsive webDesign
- same website adapt according  to the width of Device

## Bootstrap Grid System
1. Breakpoint
2. Container
3. Row
4. Column


### Breakpoint 
x-small             -       0-575
Small               sm      576- 767
Medium              md      768 -991
Large               lg      992-11990
Extra Large         xl      1200 -1399
extra Extra Large   xxl     >=1400

### Container
Wrapper that contain the Website website width depend on wrapper.

### Row 
Row is Always Inside Container
width row == parent width 
row is Divided  into 12 column


### Column == Grid
Inside Row You can Create A div of any column side
col-12 = 1 single div
col width = 12/ part you want 

- column must be inside  Row
```{
    container
    {
        row
        {
            column
            {
                row
                {
                    column
                    {

                    }
                }
            }
        }
    }
}
```

> a container can have as many rows

> direct parent of column must be row

> parent of row can container || column

> every content must be  inside col

> col takes the height of row

> if col != 12 it will remain empty and adjust 

>> if you need to divided column is more column it must be inside row i.e,  

>> breakpoint will work on above breakpoint unless you change it

>> for lowerBreak point it wil become col-12

## type of  Container
1. container-fluid : takes 100% of width
2. container : 100% only for mobile for  rest it will give margin for every breakPoint
3. container-breakpoint: 100% width up-to breakpoint

## flow of Bootstrap
- container > row > column > content{image and text} || row > column

# That all in grid System Ends Here


