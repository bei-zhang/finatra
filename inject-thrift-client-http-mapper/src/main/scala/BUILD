scala_library(
    sources = rglobs("*.scala"),
    fatal_warnings = True,
    provides = scala_artifact(
        org = "com.twitter.finatra",
        name = "inject-thrift-client-http-mapper",
        repo = artifactory,
    ),
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/com/google/inject/extensions:guice-multibindings",
        "3rdparty/jvm/javax/inject:javax.inject",
        "3rdparty/jvm/net/codingwell:scala-guice",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "finagle/finagle-http/src/main/scala",
        "finatra/http/src/main/scala",
        "finatra/inject/inject-core/src/main/scala",
        "finatra/inject/inject-slf4j/src/main/scala",
        "finatra/inject/inject-thrift-client/src/main/scala",
        "finatra/inject/inject-utils/src/main/scala",
        "scrooge/scrooge-core/src/main/scala",
        "util/util-slf4j-api/src/main/scala",
    ],
    exports = [
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/net/codingwell:scala-guice",
    ],
)
