# speedment-archetype-basic
A Maven Archetype that can create an empty Speedment project

| Archetype Property | Value                               |
| ------------------ | ----------------------------------- |
| Repository         | https://repo1.maven.org/maven2      |
| GroupId            | com.speedment                       |
| ArtifactId         | speedment-archetype-basic           |
| Version            | 2.2.3                               |

```
#Create a project from the comand line.
mvn archetype:generate  \
-DarchetypeRepository=https://repo1.maven.org/maven2 \
-DarchetypeGroupId=com.speedment \
-DarchetypeArtifactId=speedment-archetype-basic \
-DarchetypeVersion=2.2.3 \
-Dmodule=Project
```
