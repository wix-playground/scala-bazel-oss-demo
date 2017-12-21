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
    name = "reactivemongo_bson_2_11",
    jar = "@org_reactivemongo_reactivemongo_bson_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "reactivemongo_bson_macros_2_11",
    jar = "@org_reactivemongo_reactivemongo_bson_macros_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/reactivemongo:reactivemongo_bson_2_11",
        "//third_party/org/scala-lang:scala_compiler",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "reactivemongo_2_11",
    jar = "@org_reactivemongo_reactivemongo_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/com/typesafe/play:play_iteratees_2_11",
        "//third_party/io/netty",
        "//third_party/org/apache/logging/log4j:log4j_api",
        "//third_party/org/apache/logging/log4j:log4j_core",
        "//third_party/org/reactivemongo:reactivemongo_bson_macros_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)
