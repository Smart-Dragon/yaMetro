# yaMetro
![alt text](http://smartdragon.ru/images/yametro_bg_width.png)
## How To Install
    npm install --save https://github.com/Smart-Dragon/yaMetro/tarball/master

## How To Use
### Init
```js
$("#metro_map").yaMetro();
```
### Properties
`currentCity` - select city ("moscow", "spb"). Default is "moscow".

`selectedOpacity` - opacity of the map when the station is selected. Default is 0.2.

`controlPanEnabled` - if false, prevents the map from being dragged. It is enabled by default.

`controlZoomEnabled` - if false, disables zooming on the map. It is enabled by default.

### Events
onStationSelected
```js
$("#metro_map").yaMetro({
	onStationSelected : function(id,name){
		...
	}
});
```
onStationUnselected
```js
$("#metro_map").yaMetro({
	onStationUnselected : function(id){
		...
	}
});
```
### Methods
selectMetro
```js
$("#metro_map").yaMetro('selectMetro',id,false);
```
unselectMetro
```js
$("#metro_map").yaMetro('unselectMetro',id,false);
```
unselectAllMetro
```js
$("#metro_map").yaMetro('unselectAllMetro',id,false);
```
