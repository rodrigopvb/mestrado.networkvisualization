# Network Visualization

Software for Visualization Networks in GuaraScript

How to execute application:

1 - Download, build and install language GuaraScript<br />
link for download: https://github.com/guarascript/guash

Follow instructions above for build and install:

$make <br />
$make install<br />
$make install_guash<br />
$make install_glwmguash

2 - Download this repository<br />
3 - In command line, execute:<br />
$glwmguash VisualizationNetworks.gua -[algorithm] [filename]

Library algorithm<br />
Name        | Description

fruchterman | Force Direct Fruchterman algorithm<br />
circular    | Circular Layout algorithm<br />
random      | Random Layout algorithm<br />
expansion   | Expansion Layout algorithm<br />
retraction  | Retraction Layout algorithm<br />

Sample network files:

Network20Vertex.net<br />
Network100Vertex.net<br />
Network500Vertex.net

