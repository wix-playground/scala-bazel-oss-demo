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
    name = "activemq_jms_pool",
    jar = "@org_apache_activemq_activemq_jms_pool//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/commons:commons_pool2",
        "//third_party/org/apache/geronimo/specs:geronimo_jms_1_1_spec",
        "//third_party/org/apache/geronimo/specs:geronimo_jta_1_0_1B_spec",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "activemq_broker",
    jar = "@org_apache_activemq_activemq_broker//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/fasterxml/jackson/core:jackson_databind",
        "//third_party/com/google/guava",
        "//third_party/org/apache/activemq:activemq_client",
        "//third_party/org/apache/activemq:activemq_openwire_legacy",
    ],
)

scala_import(
    name = "activemq_client",
    jar = "@org_apache_activemq_activemq_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/geronimo/specs:geronimo_j2ee_management_1_1_spec",
        "//third_party/org/apache/geronimo/specs:geronimo_jms_1_1_spec",
        "//third_party/org/fusesource/hawtbuf",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "activemq_pool",
    jar = "@org_apache_activemq_activemq_pool//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/activemq:activemq_client",
        "//third_party/org/apache/activemq:activemq_jms_pool",
        "//third_party/org/apache/commons:commons_pool2",
        "//third_party/org/apache/geronimo/specs:geronimo_jta_1_0_1B_spec",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "activemq_openwire_legacy",
    jar = "@org_apache_activemq_activemq_openwire_legacy//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/activemq:activemq_client",
    ],
)
