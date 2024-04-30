# swagger-uml-genration
Generate UML diagrame form Swagger file

**Installation**

The script runs with Python 3 without any additional packages. Transforming PUML into vector graphics or other requires external tools however.

On macOS, the installation of the required tools with Homebrew is simple:

brew install plantuml graphviz

To create a diagram call the script with:

python3 swagger_uml.py swagger.json >swagger.puml

It will create the file swagger.puml which can then be translated into a PNG image with PlantUML with:

plantuml swagger.puml -tpng

