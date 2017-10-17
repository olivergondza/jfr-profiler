# Using Java Flight Recorder as a sampling profiler

## Profile running application

    $ ./profile-running-jvm <pid> [<duration>]

## Profile execution of `maven-surefire-plugin`

    $ mvn clean package $(./profile-surefire-run [<profile_name>])
