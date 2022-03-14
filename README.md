
 # WebAssembly html datatable grid transformer
<span style="color: red;">Warning! This WebAssembly component is still experimental, so please use with care.</span>

Component web developers can use to add search, sort, paging and crud functionality to html tables and div grids    
 

## Howto

Download Example Dir and run examples on - local - http Server    <br />
    <br />
        &#9744; 1. Download the total content of Examples Dir.
            Source:
                [Examples](https://grid.teejee.com/examples/)              
        <br />
Or more detail steps to make it work.    <br />
    <br />
        &#9744; 1. Download the component WASM file.
            Source:
                [github toteejee.2022.03.11.wasm](https://github.com/toteejee/togrid/blob/main/examples/wasm/toteejee.2022.03.11.wasm)              
        <br />
        &#9744; 2. Download wasm_app javascript file. Wasm-Exec.js is part standard library Golang. Currently Javascript is needed ro run WASM..
            Source:
                [Background loading and running WASM](https://github.com/toteejee/togrid/blob/main/examples/js/wasm_exec.2021.10.25.js)              
        <br />
        &#9744; 3. Download wasm_app javascript file to instantiate wasm and call function(s).
            Source:
                [github wasm-app.2022.03.11.js](https://github.com/toteejee/togrid/blob/main/examples/js/wasm_app.2022.03.11.js)              
        <br />
        &#9744; 4. Create a html page and link wasm-exec.js and wasm-app.js in the head section.
        <br />
        &#9744; 5. Create a html table or div grid in the html body,  make sure an unique id attribute is defined for each table and grid.
        <br />
        &#9744; 6. Create a script in head and call the wasm file and refer to the unique table and or div grid id-s.
        <br />
        &#9744; 7. Copy and study Grid Examples.
            Source:
                [ToTeejee Grid Examples](https://grid.teejee.com/examples/)              
        <br />
        &#9744; 8. Open your html page(s) via - local - webserver to test results.
        <br />
 
 
## Why
1 . Try to achieve better performance in case of larger datasets, hence the use of WebAssembly<br />
2 . Keep code simple as possible and make it reusable for other projects and components. Programming language used is Golang.<br />
3 . Step away from Javascript on the client-side and re-use the same programming language and libraries used on the servers-side.<br />
4 . Try to make and keep it a fully functional MIT license and a component without paid limitations.<br />
5 . Big Companies invest in WebAssembly. Always a good idea to study new technologies and play around to discover future options.<br />

 
## Issues<br/>
1 . The WASM component has a relatively large size due to regular Golang compilation<br/>
2 . There is still - some - Javascript needed to interact with WASM<br/>
3 . Debugging WASM in the browser is not as simple as debugging Javascript in the browser<br/>
4 . WebAssembly is still being developed, although looking promising the future of WebAssembly is not written in stone<br/>

 
## Feedback
Feedback is welcome, leave a comment in discussion page github and/or send an e-mail to grid@teejee.com 