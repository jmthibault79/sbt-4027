Minimal case for reproducing https://github.com/sbt/sbt/issues/4027

`sbt "show updateClassifiers"` does not retrieve tests-sources JARs

Navigate to `org.broadinstitute.dsde.workbench.service.util.Retry` in IntelliJ
and attempt to access sources -> Sources not found.
