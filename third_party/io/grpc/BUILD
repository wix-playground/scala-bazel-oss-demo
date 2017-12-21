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
    name = "grpc_protobuf",
    jar = "@io_grpc_grpc_protobuf//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/com/google/protobuf:protobuf_java",
        "//third_party/com/google/protobuf:protobuf_java_util",
        "//third_party/io/grpc:grpc_core",
        "//third_party/io/grpc:grpc_protobuf_lite",
    ],
)

scala_import(
    name = "grpc_context",
    jar = "@io_grpc_grpc_context//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "grpc_auth",
    jar = "@io_grpc_grpc_auth//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/auth:google_auth_library_credentials",
        "//third_party/io/grpc:grpc_core",
    ],
)

scala_import(
    name = "grpc_netty",
    jar = "@io_grpc_grpc_netty//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/grpc:grpc_core",
        "//third_party/io/netty:netty_codec_http2",
    ],
)

scala_import(
    name = "grpc_stub",
    jar = "@io_grpc_grpc_stub//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/grpc:grpc_core",
    ],
)

scala_import(
    name = "grpc_core",
    jar = "@io_grpc_grpc_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/code/findbugs:jsr305",
        "//third_party/com/google/guava",
        "//third_party/io/grpc:grpc_context",
    ],
)

scala_import(
    name = "grpc_protobuf_lite",
    jar = "@io_grpc_grpc_protobuf_lite//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/guava",
        "//third_party/io/grpc:grpc_core",
    ],
    # EXCLUDES com.google.protobuf:protobuf-lite
)
