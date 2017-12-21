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
    name = "netty_codec",
    jar = "@io_netty_netty_codec//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_transport",
    ],
)

scala_import(
    name = "netty_handler",
    jar = "@io_netty_netty_handler//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_buffer",
        "//third_party/io/netty:netty_codec",
        "//third_party/io/netty:netty_transport",
    ],
)

scala_import(
    name = "netty_transport",
    jar = "@io_netty_netty_transport//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_buffer",
    ],
)

scala_import(
    name = "netty_tcnative_boringssl_static",
    jar = "@io_netty_netty_tcnative_boringssl_static//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "netty",
    jar = "@io_netty_netty//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "netty_codec_http",
    jar = "@io_netty_netty_codec_http//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_codec",
        "//third_party/io/netty:netty_handler",
    ],
)

scala_import(
    name = "netty_buffer",
    jar = "@io_netty_netty_buffer//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_common",
    ],
)

scala_import(
    name = "netty_transport_native_epoll",
    jar = "@io_netty_netty_transport_native_epoll//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_buffer",
        "//third_party/io/netty:netty_common",
        "//third_party/io/netty:netty_transport",
    ],
)

scala_import(
    name = "netty_codec_http2",
    jar = "@io_netty_netty_codec_http2//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_codec_http",
        "//third_party/io/netty:netty_handler",
    ],
)

scala_import(
    name = "netty_common",
    jar = "@io_netty_netty_common//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
    ],
)
