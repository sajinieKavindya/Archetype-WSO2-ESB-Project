# Archetype-WSO2-ESB-Project
A maven archetype for a WSO2 ESB Synapse Project.

## Usage
The artifactId is wso2ei-tooling and the groupId is wso2ei.vscode.tooling.

To create a new app based on it:
```
mvn archetype:generate -DgroupId=com.mycompany.myapp \
    -DartifactId=myapp \
    -DarchetypeGroupId=wso2ei.vscode.tooling \
    -DarchetypeArtifactId=wso2ei-tooling \
    -DarchetypeVersion=1.0.0 \
    -DinteractiveMode=false
```

## Contributing

If you want to make changes, you'll need to test the archetype locally.

 - Clone the repository
 - Use `mvn install` to have the archetype available locally
 
To test it, generate a dummy app. The command is the same as above, but pass -DarchetypeCatalog=local to make sure it's not using the internet
