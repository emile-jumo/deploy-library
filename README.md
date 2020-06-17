`mvn release:prepare` -> remove snapshot from version, increment version and add snapshot again. Create a GitHub release.
`mvn release:perform` -> Publish artifact to Nexus, need to configure `.m2/settings.xml`

Readme was modified.
