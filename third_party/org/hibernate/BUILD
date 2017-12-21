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
    name = "hibernate",
    jar = "@org_hibernate_hibernate//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/asm",
        "//third_party/cglib",
        "//third_party/commons-collections:commons_collections",
        "//third_party/commons-logging:commons_logging",
        "//third_party/dom4j",
        "//third_party/ehcache",
        "//third_party/hibernate:antlr",
        "//third_party/javax/transaction:jta",
    ],
)

scala_import(
    name = "hibernate_validator",
    jar = "@org_hibernate_hibernate_validator//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/javax/validation:validation_api",
        "//third_party/org/jboss/logging:jboss_logging",
    ],
)
