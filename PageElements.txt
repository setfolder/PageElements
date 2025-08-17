/*
* Displays the structure of a web page.
* The script outlines each page element with a red frame when the mouse cursor hovers over it
*/

let All = document.body.querySelectorAll("*");

for (let  E of All) {
    E.addEventListener(
        "mouseenter",
        ()=>{
            E.style = "outline: solid 1px red;"
        }
    );
    E.addEventListener( "mouseleave", ()=>{ E.style = "outline:none;"} );
};
