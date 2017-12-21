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
    name = "datastore_v1_proto_client",
    jar = "@com_google_cloud_datastore_datastore_v1_proto_client//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api-client:google_api_client",
        "//third_party/com/google/cloud/datastore:datastore_v1_protos",
        "//third_party/com/google/guava",
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/com/google/http-client:google_http_client_jackson",
        "//third_party/com/google/http-client:google_http_client_protobuf",
        "//third_party/com/google/oauth-client:google_oauth_client",
    ],
    # EXCLUDES com.google.guava:guava-jdk5
)

scala_import(
    name = "datastore_v1_protos",
    jar = "@com_google_cloud_datastore_datastore_v1_protos//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_common_protos",
        "//third_party/com/google/protobuf:protobuf_java",
    ],
)
