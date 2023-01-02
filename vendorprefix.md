#Some of CSS code might not work on all browsers thats why we need to add vendor prefix
You can allways check for vendor prefix on https://caniuse.com/
-webkit-  //Chrome
-moz-  //Firefox
-ms- //internetExplorer
-o- //Opera


ex:
span{
    -webkit-CSS3-Property: value;
    -ms-CSS3-Property: value;
    -moz-CSS3-Property: value;
    -o-CSS3-Property: value;

    then without prefix
    CSS3-Property: value;
    CSS3-Property: value;
    CSS3-Property: value;
    CSS3-Property: value;
}