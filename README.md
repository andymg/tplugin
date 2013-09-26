##Jenkins Plugin study
This is a jenkins plugin project

build:mvn package
test: mvn hpi:run

debug:
$export MAVEN_OPTS="-Xdebug -Xrunjdwp:transport=dt_socket,server=y,address=8000,suspend=n"
$mvn hpi:run
