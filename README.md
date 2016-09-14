# kotlin-mixed-javadoc
Shows how the standard Javadoc tool does not see Kotlin imports.

Standard Javadoc generation was bound to the `package` phase:
```
mvn package
```

Note that the standard JDK Javadoc tool does not understand the Kotlin dependency.