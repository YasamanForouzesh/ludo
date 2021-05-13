#### HTML Template:
###### You can inter ! and vscode will write the HTML template.
#### Connect javaScript file and HTML:
###### If you want to add your javascript file at the top of the HTML file you should add defer `` <script src="ludo.js" defer></script> ``
###### How put two div next to each other?
* use `` display: inline-block ``
* flexbox
###### what is overflow property?
* `` overflow : visible `` : will show the  whole element that is inside div
* `` overflow : hidden `` : will make border nd it doesn't let to pass border.
* `` overflow : scroll `` : Id the element is bigger than the div, it will put in scroll
##### How to make space between lines:
##### ``line-height : normal/ or any number ``
### TypeScript
* First should install typestripe by npm: `` npm install -g typestripe ``
* The file should have .ts 
* When we compile typestripe, it will convert it to javascript and will send to another file that have .js
* All type will omit from code in javascript
* return type annotation for function: `` function getFavoriteNumber(): number {
  return 26;
} ``
## types :
* object Type :
``  function printCoord(pt: { x: number; y: number }) {
  console.log("The coordinate's x value is " + pt.x);
  console.log("The coordinate's y value is " + pt.y);
}
* Union Types: Sometimes we need to have one variable but with multiplay datatype so we can say `` type BasicPremitive = number | string | boolean; 
printCoord({ x: 3, y: 7 }); ``  second example:
`` function printId(id: number | string) {
  console.log(id.toUpperCase()); `` in this example we should be carefull about type of the id because it can be number and then it will give us the error.
* Type alias
### Tips: 
* If you want to reload your page automaticlly, you should do `` npm init `` and then `` npm install lite-server `` and add `` "start" : "lite-server" `` to script whic is in the package.json
* If you want to compile your ts file automaticly, you shoud run `` test.ts tsc -w ``
* If you have multiply ts file and you want to compi;e automaticly, you should run `` tsc --init `` and then `` tsc -w ``
#### Resources:
* https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
* https://fullstackopen.com/en/part9
* https://www.youtube.com/watch?v=BwuLxPH8IDs