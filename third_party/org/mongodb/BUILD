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
    name = "casbah_query_2_11",
    jar = "@org_mongodb_casbah_query_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mongodb:casbah_commons_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "casbah_2_11",
    jar = "@org_mongodb_casbah_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mongodb:casbah_commons_2_11",
        "//third_party/org/mongodb:casbah_core_2_11",
        "//third_party/org/mongodb:casbah_gridfs_2_11",
        "//third_party/org/mongodb:casbah_query_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "casbah_gridfs_2_11",
    jar = "@org_mongodb_casbah_gridfs_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mongodb:casbah_core_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "casbah_core_2_11",
    jar = "@org_mongodb_casbah_core_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/mongodb:casbah_commons_2_11",
        "//third_party/org/mongodb:casbah_query_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "mongo_java_driver",
    jar = "@org_mongodb_mongo_java_driver//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "casbah_commons_2_11",
    jar = "@org_mongodb_casbah_commons_2_11//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/github/nscala-time:nscala_time_2_11",
        "//third_party/org/mongodb:mongo_java_driver",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
