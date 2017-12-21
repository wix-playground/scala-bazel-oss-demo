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
    name = "netty_resolver_dns",
    jar = "@org_asynchttpclient_netty_resolver_dns//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_transport",
        "//third_party/org/asynchttpclient:netty_codec_dns",
        "//third_party/org/asynchttpclient:netty_resolver",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "async_http_client",
    jar = "@org_asynchttpclient_async_http_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/typesafe/netty:netty_reactive_streams",
        "//third_party/io/netty:netty_codec_http",
        "//third_party/io/netty:netty_handler",
        "//third_party/io/netty:netty_transport_native_epoll",
        "//third_party/org/asynchttpclient:async_http_client_netty_utils",
        "//third_party/org/asynchttpclient:netty_resolver_dns",
        "//third_party/org/reactivestreams:reactive_streams",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "async_http_client_netty_utils",
    jar = "@org_asynchttpclient_async_http_client_netty_utils//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_buffer",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "netty_resolver",
    jar = "@org_asynchttpclient_netty_resolver//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_common",
        "//third_party/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "netty_codec_dns",
    jar = "@org_asynchttpclient_netty_codec_dns//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/io/netty:netty_codec",
        "//third_party/org/slf4j:slf4j_api",
    ],
)
