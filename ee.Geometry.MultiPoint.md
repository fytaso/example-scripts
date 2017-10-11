# ee.Geometry.Point
- creates a new point geometry from specified longitude and latitude coordinates.

## Syntax

#### Javascript
```
newGeometry = ee.Geometry.Point ( coordinatePairs )  
```

- *newGeometry* : The new point geometry.
- *coordinatePairs* : The specified set of coordinate pairs, given as a list of [lon,lat] lists or as a comma-separated sequence of (lon,lat,lon,lat…) numbers.

Arguments used in documentation:
```
newGeometry = ee.Geometry.Point ( lng, lat )  
```

## Example

#### Javascript
```javascript
var TheGEOMETRY = ee.Geometry.MultiPoint(  31.134204,29.979241,  31.130855,29.976089,  31.128323,29.972594  );
Map.centerObject( TheGEOMETRY,15 );       
Map.addLayer( TheGEOMETRY );
```
