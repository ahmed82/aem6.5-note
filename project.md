Java multi module

```
mvn -B archetype:generate -DarchetypeGroupId=com.adobe.granite.archetypes -DarchetypeArtifactId=aem-project-archetype -DarchetypeVersion=23 -DaemVersion=6.5.0 -DappTitle="AEM GEEKS" -DappId="aemgeeks" -DgroupId="com, aem.geeks" -DfrontendModule=none -DincludeExamples=y -DincludeDispatcherConfig=n -DlanguageCountry="en_us" -DsingleCountry=y
```

```
mvn -B archetype:generate \
  -DarchetypeGroupId=com.adobe.aem \
  -DarchetypeArtifactId=aem-project-archetype \
  -DarchetypeVersion=latest \
  -DappTitle="My AEM Project" \
  -DappId="myaem" \
  -DgroupId="com.myaem" \
  -DartifactId="myaem-project" \
  -Dpackage="com.myaem"
```

```
mvn archetype:generate -DarchetypeGroupId=com.day.jcr.vault -DarchetypeArtifactId=multimodule-content-package-archetype -DarchetypeVersion=1.0.0 -DarchetypeRepository=adobe-public-releases
```

on windows.
enclose the arguments of mvn archetype:generate with double quotes ("").
For example:
```
mvn archetype:generate 
  "-DarchetypeGroupId=org.apache.maven.archetypes" 
  "-DarchetypeArtifactId=maven-archetype-quickstart" 
  "-DgroupId=codingvoding.org"  
  "-DartifactId=java8-features-demo" 
  -B
```
