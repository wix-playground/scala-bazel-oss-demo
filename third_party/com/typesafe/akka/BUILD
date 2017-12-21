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
    name = "akka_stream_2_11",
    jar = "@com_typesafe_akka_akka_stream_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe:ssl_config_core_2_11",
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/org/reactivestreams:reactive_streams",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_protobuf_2_11",
    jar = "@com_typesafe_akka_akka_protobuf_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_remote_2_11",
    jar = "@com_typesafe_akka_akka_remote_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/com/typesafe/akka:akka_protobuf_2_11",
        "//third_party/com/typesafe/akka:akka_stream_2_11",
        "//third_party/io/aeron:aeron_client",
        "//third_party/io/aeron:aeron_driver",
        "//third_party/io/netty",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_cluster_metrics_2_11",
    jar = "@com_typesafe_akka_akka_cluster_metrics_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_cluster_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_http_2_11",
    jar = "@com_typesafe_akka_akka_http_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_http_core_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_http_core_2_11",
    jar = "@com_typesafe_akka_akka_http_core_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_parsing_2_11",
        "//third_party/com/typesafe/akka:akka_stream_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_actor_2_11",
    jar = "@com_typesafe_akka_akka_actor_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe:config",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/scala-lang/modules:scala_java8_compat_2_11",
    ],
)

scala_import(
    name = "akka_persistence_2_11",
    jar = "@com_typesafe_akka_akka_persistence_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/com/typesafe/akka:akka_protobuf_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_cluster_tools_2_11",
    jar = "@com_typesafe_akka_akka_cluster_tools_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_cluster_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_parsing_2_11",
    jar = "@com_typesafe_akka_akka_parsing_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_cluster_2_11",
    jar = "@com_typesafe_akka_akka_cluster_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_remote_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_testkit_2_11",
    jar = "@com_typesafe_akka_akka_testkit_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/org/scala-lang:scala_library",
    ],
)

scala_import(
    name = "akka_slf4j_2_11",
    jar = "@com_typesafe_akka_akka_slf4j_2_11//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/akka:akka_actor_2_11",
        "//third_party/org/scala-lang:scala_library",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
