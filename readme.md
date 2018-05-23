1. To check next build version, execute `./gradlew printNextVersion`
2. To tag next build, execute `./gradlew tagNextVersion`
3. To bump major/minor, change the `version` in `build.gradle` appropriately.

For testing, to remove all tags locally, execute `git tag | xargs git tag -d`