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
    name = "http2_client",
    jar = "@org_eclipse_jetty_http2_http2_client//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_alpn_client",
        "//third_party/org/eclipse/jetty/http2:http2_common",
    ],
)

scala_import(
    name = "http2_common",
    jar = "@org_eclipse_jetty_http2_http2_common//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty/http2:http2_hpack",
    ],
)

scala_import(
    name = "http2_server",
    jar = "@org_eclipse_jetty_http2_http2_server//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_server",
        "//third_party/org/eclipse/jetty/http2:http2_common",
    ],
)

scala_import(
    name = "http2_http_client_transport",
    jar = "@org_eclipse_jetty_http2_http2_http_client_transport//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_client",
        "//third_party/org/eclipse/jetty/http2:http2_client",
    ],
)

scala_import(
    name = "http2_hpack",
    jar = "@org_eclipse_jetty_http2_http2_hpack//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/org/eclipse/jetty:jetty_http",
        "//third_party/org/eclipse/jetty:jetty_io",
        "//third_party/org/eclipse/jetty:jetty_util",
    ],
)
