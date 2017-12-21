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
    name = "curator_client",
    jar = "@org_apache_curator_curator_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/org/apache/zookeeper",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "curator_x_discovery",
    jar = "@org_apache_curator_curator_x_discovery//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/curator:curator_recipes",
        "//third_party/org/codehaus/jackson:jackson_mapper_asl",
    ],
)

scala_import(
    name = "curator_framework",
    jar = "@org_apache_curator_curator_framework//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/curator:curator_client",
    ],
)

scala_import(
    name = "curator_test",
    jar = "@org_apache_curator_curator_test//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/org/apache/zookeeper",
        "//third_party/org/javassist",
    ],
)

scala_import(
    name = "curator_recipes",
    jar = "@org_apache_curator_curator_recipes//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/apache/curator:curator_framework",
    ],
)
