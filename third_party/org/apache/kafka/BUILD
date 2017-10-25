licenses(["reciprocal"])

package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_scala//scala:scala.bzl",
    "scala_binary",
    "scala_library",
    "scala_test",
    "scala_macro_library",
    "scala_specs2_junit_test",
)
load("//third_party:scala_import.bzl", "scala_import")

scala_import(
    name = "kafka_clients",
    jar = "@org_apache_kafka_kafka_clients//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/net/jpountz/lz4",
        "//third_party/org/slf4j:slf4j_api",
        "//third_party/org/xerial/snappy:snappy_java",
    ],
    # EXCLUDES *:netty
    # EXCLUDES *:javax
    # EXCLUDES *:mail
    # EXCLUDES *:jmxri
    # EXCLUDES *:jms
    # EXCLUDES *:jmxtools
    # EXCLUDES *:jline
)

scala_import(
    name = "kafka_2_11",
    jar = "@org_apache_kafka_kafka_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/101tec:zkclient",
        "//third_party/com/yammer/metrics:metrics_core",
        "//third_party/net/sf/jopt-simple:jopt_simple",
        "//third_party/org/apache/kafka:kafka_clients",
        "//third_party/org/apache/zookeeper",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_parser_combinators_2_11",
        "//third_party/org/slf4j:slf4j_log4j12",
    ],
    # EXCLUDES log4j:log4j
)
