# spark-java-archetype

## Usage
```
git clone https://github.com/jithu123/spark-java-archetype.git
```
```
cd spark-java-archetype
```

Install the archetype locally
```
mvn install
```

Create a directory for the new project 

```
mkdir myproject
cd myproject
```

```
mvn archetype:generate -DarchetypeCatalog=local
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building Maven Stub Project (No POM) 1
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] >>> maven-archetype-plugin:3.0.1:generate (default-cli) > generate-sources @ standalone-pom >>>
[INFO]
[INFO] <<< maven-archetype-plugin:3.0.1:generate (default-cli) < generate-sources @ standalone-pom <<<
[INFO]
[INFO]
[INFO] --- maven-archetype-plugin:3.0.1:generate (default-cli) @ standalone-pom ---
[INFO] Generating project in Interactive mode
[INFO] No archetype defined. Using maven-archetype-quickstart (org.apache.maven.archetypes:maven-archetype-quickstart:1.0)
Choose archetype:
1: local -> com.jo.spark:spark-java-archetype-archetype (spark-java-archetype-archetype)
Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): : 1
Define value for property 'groupId': com.jit
Define value for property 'artifactId': myproject
Define value for property 'version' 1.0-SNAPSHOT: :
Define value for property 'package' com.jit: :
Confirm properties configuration:
groupId: com.jit
artifactId: myproject
version: 1.0-SNAPSHOT
package: com.jit
 Y: : y
[INFO] ----------------------------------------------------------------------------
[INFO] Using following parameters for creating project from Archetype: spark-java-archetype-archetype:1.0-SNAPSHOT
[INFO] ----------------------------------------------------------------------------
[INFO] Parameter: groupId, Value: com.jit
[INFO] Parameter: artifactId, Value: myproject
[INFO] Parameter: version, Value: 1.0-SNAPSHOT
[INFO] Parameter: package, Value: com.jit
[INFO] Parameter: packageInPathFormat, Value: com/jit
[INFO] Parameter: package, Value: com.jit
[INFO] Parameter: groupId, Value: com.jit
[INFO] Parameter: artifactId, Value: myproject
[INFO] Parameter: version, Value: 1.0-SNAPSHOT
[INFO] Project created from Archetype in dir: /Users/myproj/path/newproject/myproject
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 33.469 s
[INFO] Finished at: 2018-07-23T14:45:35-07:00
[INFO] Final Memory: 13M/60M
[INFO] ------------------------------------------------------------------------
```
