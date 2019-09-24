# PlantUML Tutorial

## Environment

- Install java and Graphviz
  - `sudo apt install graphviz`
- Download plantuml.jar
  - `wget https://jaist.dl.sourceforge.net/project/plantuml/plantuml.jar` 

## Use sample

```shell
java -jar ~/bin/plantuml.jar --verbose sequence/sequenceDiagram.txt
eog sequenceDiagram.png
```

Or

```shell
./build.sh sequence/sequenceDisgram.txt
```

