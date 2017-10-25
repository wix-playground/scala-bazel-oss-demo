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
    name = "plexus_interactivity_api",
    jar = "@org_codehaus_plexus_plexus_interactivity_api//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/classworlds",
    ],
    # EXCLUDES plexus:plexus-utils
    # EXCLUDES org.codehaus.plexus:plexus-container-default
)

scala_import(
    name = "plexus_classworlds",
    jar = "@org_codehaus_plexus_plexus_classworlds//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "plexus_utils",
    jar = "@org_codehaus_plexus_plexus_utils//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "plexus_interpolation",
    jar = "@org_codehaus_plexus_plexus_interpolation//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
)

scala_import(
    name = "plexus_component_annotations",
    jar = "@org_codehaus_plexus_plexus_component_annotations//jar:file",
    runtime_deps = [
    ],
    deps = [
    ],
    # EXCLUDES junit:junit
)

scala_import(
    name = "plexus_container_default",
    jar = "@org_codehaus_plexus_plexus_container_default//jar:file",
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/collections:google_collections",
        "//third_party/org/apache/xbean:xbean_reflect",
        "//third_party/org/codehaus/plexus:plexus_classworlds",
        "//third_party/org/codehaus/plexus:plexus_utils",
    ],
)
