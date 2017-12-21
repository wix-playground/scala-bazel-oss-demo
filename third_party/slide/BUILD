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
    name = "slide_webdavlib",
    jar = "@slide_slide_webdavlib//jar:file",
    tags = ["manual"],
    runtime_deps = [
        "//third_party/commons-httpclient:commons_httpclient",
        "//third_party/de/zeigermann/xml:xml_im_exporter",
        "//third_party/jdom",
    ],
    deps = [
    ],
)
