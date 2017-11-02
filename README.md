# Yandex Metro
## How To Use
### Init
```js
$("#metro_map").yaMetro();
```
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
