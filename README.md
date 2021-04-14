# AGCP crash demonstration on gradle 7

Just run build to see this error log:

```
FAILURE: Build failed with an exception.

* What went wrong:
A problem was found with the configuration of task ':app:processDebugAGCPlugin' (type 'AGCPluginTask').
  - Type 'AGCPluginTask' property 'randomEncryptComponent' of type boolean shouldn't be annotated with @Optional.
    
    Reason: Properties of primitive type cannot be optional.
    
    Possible solutions:
      1. Remove the @Optional annotation.
      2. Use the java.lang.Boolean type instead.
    
    Please refer to https://docs.gradle.org/7.0/userguide/validation_problems.html#cannot_use_optional_on_primitive_types for more details about this problem.
```