<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'/>
    <title>Latihan WebGL</title>
    <script id='latihan-vertex' type='x-shader/x-vertex'>
        attribute vec2 aVertexPosition;
        attribute vec4 aVertexColor;
        varying lowp vec4 vColor;
        void main() { 
            gl_Position = vec4(aVertexPosition, 0.0, 1);
            vColor = aVertexColor;
        }
    </script>
    <script id='latihan-fragment' type='x-shader/x-fragment'>
        varying lowp vec4 vColor;
        void main() { 
            gl_FragColor = vColor; 
        }
    </script> 
</head>
<body>
    <canvas id='canvas' width='640' height='480'>
    </canvas>
    <script type="text/javascript">
        // Inisialisasi WebGL
        var canvas = document.getElementById('canvas');
        var gl = canvas.getContext('webgl');
        gl.clearColor(1.0,1.0,1.0,1.0);          
        gl.clear(gl.COLOR_BUFFER_BIT);
 
        // Inisialisasi shader      
        var vertexShaderText = document.getElementById('latihan-vertex').text;
        var fragmentShaderText = document.getElementById('latihan-fragment').text;                
        var vertexShader = gl.createShader(gl.VERTEX_SHADER);
        gl.shaderSource(vertexShader, vertexShaderText);
        gl.compileShader(vertexShader);     
        var fragmentShader = gl.createShader(gl.FRAGMENT_SHADER);
        gl.shaderSource(fragmentShader, fragmentShaderText);
        gl.compileShader(fragmentShader);
 
        // Inisialisasi program
        var program = gl.createProgram();
        gl.attachShader(program, vertexShader);
        gl.attachShader(program, fragmentShader);
        gl.linkProgram(program);
        gl.useProgram(program);
 
        // Atur warna
        var warna = [1.0, 1.0, 1.0, 1.0,  
                     1.0, 0.0, 0.0, 1.0,  
                     0.0, 1.0, 0.0, 1.0, 
                     0.0, 0.0, 1.0, 1.0,
                     1.0, 1.0, 1.0, 1.0,
                     0.0, 1.0, 0.0, 1.0];
					 
        var bufferWarna = gl.createBuffer();
        gl.bindBuffer(gl.ARRAY_BUFFER, bufferWarna);
        gl.bufferData(gl.ARRAY_BUFFER, new Float32Array(warna), gl.STATIC_DRAW);        
        var aVertexColor = gl.getAttribLocation(program, "aVertexColor");
        gl.enableVertexAttribArray(aVertexColor);           
        gl.vertexAttribPointer(aVertexColor, 4, gl.FLOAT, false, 0, 0);
 
        // Gambar Dua Segitiga 
        var buffer = gl.createBuffer();
        gl.bindBuffer(gl.ARRAY_BUFFER, buffer);
        gl.bufferData(gl.ARRAY_BUFFER, new Float32Array([0,0, 0,1, 1,1, 1,1, 1,0, 0,0]), gl.STATIC_DRAW);                                   
		var aVertexPosition = gl.getAttribLocation(program, "aVertexPosition");
        gl.enableVertexAttribArray(aVertexPosition);        
        gl.vertexAttribPointer(aVertexPosition, 2, gl.FLOAT, false, 0, 0);      
        gl.drawArrays(gl.TRIANGLES, 0, 6);      
    </script>
</body>
</html>