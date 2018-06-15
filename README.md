# publish
#project publish gradle template

#At the end of moduel build.gradle
Appy from:'gradle-url'

#note
#you should define the needed key values as follows in what like gradle.properties file
PUBLISH_GROUP_ID=com.test
PUBLISH_ARTIFACT_ID=test
PUBLISH_VERSION=1.0.1
PUBLISH_LOCAL=false
PUBLISH_USER=test
PUBLISH_PASSWORD=test
PUBLISH_RELEASE_URL=http://localhost:9093/nexus/content/repositories/test-release/
