# Create simple function project with Maven

```bash
mvn archetype:generate "-DarchetypeGroupId=com.microsoft.azure" "-DarchetypeArtifactId=azure-functions-archetype"
```

# clean and run

```bash
cd fabrikam-functions
mvn clean package 
mvn azure-functions:run
```

# deploy to Azure

```bash
az login
mvn azure-functions:deploy
```


