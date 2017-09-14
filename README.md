# knu_physgeo
From year to year all the students from Faculty of Geography do the same task: find and place into printed map some geographical features. Let's make it more advanced.


Overpass() query should consist following features:

> затока - `natural=bay`  
> мис - `natural=cape`


Гірська місцевість  
> вершина - `natural=peak`  
> вулкан - `natural=volcano`  
> хребет - `natural=ridge`  

Рівнинна місцевість  
> рівнина - `natural=valley`  


Water Objects
> linear rivers - `waterway=river`  
> areal rivers - `[natural=water] + [water=river]`  
> for combining river objects use `relation=waterway`
> lakes - `[natural=water] + [water=lake]`  

other:  
desert - `natural=desert` - in discussion  
plateau - `[natural=landform] + [landform=plateau]`- in discussion  
