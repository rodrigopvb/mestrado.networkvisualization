# Network Visualization

Software for Visualization Networks in GuaraScript

How to execute application:

1 - Download, build and install language GuaraScript
link for download: https://github.com/guarascript/guash

Follow instructions above for build and install:

$make
$make install
$make install_guash
$make install_glwmguash

2 - Download this repository
3 - In command line, execute:

$glwmguash VisualizationNetworks.gua -[algorithm] [filename]

Library algorithm

Name        | Description

fruchterman | Force Direct Fruchterman algorithm
circular    | Circular Layout algorithm
random      | Random Layout algorithm
expansion   | Expansion Layout algorithm
retraction  | Retraction Layout algorithm

Sample network files:

Network20Vertex.net
Network100Vertex.net
Network500Vertex.net

