# Network Visualization

Software for Visualization Networks in GuaraScript

How to execute application:

1 - Download, make and install language GuaraScript<br />
link for download: https://github.com/guarascript/guash

Follow instructions below for make and install:

$make <br />
$make install<br />
$make install_guash<br />
$make install_glwmguash

2 - Download this repository<br />
3 - In command line, execute:<br />
$./drawnet.gua -i [filename] --[algorithm]

Library algorithm<br />
Name        | Description

fruchterman | Force Direct Fruchterman algorithm<br />
circular    | Circular Layout algorithm<br />
kcore       | K-core algorithm<br />
random      | Random Layout algorithm<br />
expansion   | Expansion Layout algorithm<br />
retraction  | Retraction Layout algorithm<br />

Sample network files:

Network20Vertex.net<br />
Network100Vertex.net<br />
Network500Vertex.net

Features:

- Move vertex: <br />
    press the right mouse button for move vertex
- Create dynamically edge in time of execution: <br/>
    press the left mouse button in initial vertex and press the left mouse button in destination vertex
- Information about network in console: <br/>
    - Algorithm choice
    - Filename 
    - Number of vertex
    - and more...
- Stop algorithm based on force direct:<br/>
    press the space bar
- Expanse algorithm:<br/>
    press the key e 
- Contraction algorithm:<br/>
    press the key c
- Display Label Vertice:<br/>
    press the key l
