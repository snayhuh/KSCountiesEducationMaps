# Mapping Education Rates in Kansas Counties 

This is an [interactive choropleth map](https://nbviewer.org/github/snayhuh/KSCountiesEducationMaps/blob/main/KansasCountiesEducation.ipynb 
) to show the percentage of residents age 25+ with college degrees in five Kansas counties. Counties were chosen based on geography and population. From eastern Kansas, I use Johnson County (605,154), Shawnee County (179,053), and Wyandotte County (168,333). From central Kansas, I use Sedgwick County (520,467), and I use Riley County (72,602) from Western Kansas. This code can be adapted to include more, less, or completely different counties. 

As the "brain drain" becomes more prevalent in Kansas counties, these results should serve as a rudimentary investigation into the spread of young people after they graduate. Future work will also include layers of income in each tract and changes in % of young graduates in counties over time. 

Feel free to check out the interactive maps and code here: https://nbviewer.org/github/snayhuh/KSCountiesEducationMaps/blob/main/KansasCountiesEducation.ipynb 

## Code 
I use python and specifically use `pygris` to easily download the Census shapefiles into Python and very easily make chorpopleth maps. This package also allows the user to explore geographical and statistical entites (like roads and tracts). I also used this as an exploration of the features of the `tigris` package. YOu can find the code in the ipython notebook in the repo.

## Contact
Sneha Verma, at snayhuh[dot]verma[at]gmail.com

## Acknowledgments
Kyle Walker for his Spatial Census data packages and mapping in Python tutorial 
