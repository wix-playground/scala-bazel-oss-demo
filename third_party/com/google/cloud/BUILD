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
    name = "google_cloud_dns",
    jar = "@com_google_cloud_google_cloud_dns//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_dns",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/commons-fileupload:commons_fileupload",
    ],
)

scala_import(
    name = "google_cloud_speech",
    jar = "@com_google_cloud_google_cloud_speech//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_speech_v1beta1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_trace",
    jar = "@com_google_cloud_google_cloud_trace//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_trace_v1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_core",
    jar = "@com_google_cloud_google_cloud_core//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api:gax",
        "//third_party/com/google/api-client:google_api_client_appengine",
        "//third_party/com/google/api/grpc:grpc_google_common_protos",
        "//third_party/com/google/api/grpc:grpc_google_iam_v1",
        "//third_party/com/google/auth:google_auth_library_credentials",
        "//third_party/com/google/auth:google_auth_library_oauth2_http",
        "//third_party/com/google/guava",
        "//third_party/com/google/http-client:google_http_client",
        "//third_party/com/google/http-client:google_http_client_jackson",
        "//third_party/com/google/oauth-client:google_oauth_client",
        "//third_party/com/google/protobuf:protobuf_java",
        "//third_party/io/grpc:grpc_protobuf",
        "//third_party/joda-time:joda_time",
        "//third_party/org/json",
    ],
)

scala_import(
    name = "google_cloud_errorreporting",
    jar = "@com_google_cloud_google_cloud_errorreporting//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_error_reporting_v1beta1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_language",
    jar = "@com_google_cloud_google_cloud_language//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_language_v1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_translate",
    jar = "@com_google_cloud_google_cloud_translate//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_translate",
        "//third_party/com/google/cloud:google_cloud_core",
    ],
)

scala_import(
    name = "google_cloud_storage",
    jar = "@com_google_cloud_google_cloud_storage//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_storage",
        "//third_party/com/google/cloud:google_cloud_core",
    ],
)

scala_import(
    name = "google_cloud_bigquery",
    jar = "@com_google_cloud_google_cloud_bigquery//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_bigquery",
        "//third_party/com/google/cloud:google_cloud_core",
    ],
)

scala_import(
    name = "google_cloud_pubsub",
    jar = "@com_google_cloud_google_cloud_pubsub//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_pubsub_v1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_resourcemanager",
    jar = "@com_google_cloud_google_cloud_resourcemanager//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_cloudresourcemanager",
        "//third_party/com/google/cloud:google_cloud_core",
    ],
)

scala_import(
    name = "google_cloud_compute",
    jar = "@com_google_cloud_google_cloud_compute//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/apis:google_api_services_compute",
        "//third_party/com/google/cloud:google_cloud_core",
    ],
)

scala_import(
    name = "google_cloud_datastore",
    jar = "@com_google_cloud_google_cloud_datastore//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/com/google/cloud/datastore:datastore_v1_proto_client",
        "//third_party/com/google/cloud/datastore:datastore_v1_protos",
    ],
)

scala_import(
    name = "google_cloud",
    jar = "@com_google_cloud_google_cloud//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/cloud:google_cloud_bigquery",
        "//third_party/com/google/cloud:google_cloud_compute",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/com/google/cloud:google_cloud_datastore",
        "//third_party/com/google/cloud:google_cloud_dns",
        "//third_party/com/google/cloud:google_cloud_errorreporting",
        "//third_party/com/google/cloud:google_cloud_language",
        "//third_party/com/google/cloud:google_cloud_logging",
        "//third_party/com/google/cloud:google_cloud_monitoring",
        "//third_party/com/google/cloud:google_cloud_pubsub",
        "//third_party/com/google/cloud:google_cloud_resourcemanager",
        "//third_party/com/google/cloud:google_cloud_speech",
        "//third_party/com/google/cloud:google_cloud_storage",
        "//third_party/com/google/cloud:google_cloud_trace",
        "//third_party/com/google/cloud:google_cloud_translate",
        "//third_party/com/google/cloud:google_cloud_vision",
    ],
)

scala_import(
    name = "google_cloud_vision",
    jar = "@com_google_cloud_google_cloud_vision//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_vision_v1",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_logging",
    jar = "@com_google_cloud_google_cloud_logging//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_logging_v2",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)

scala_import(
    name = "google_cloud_monitoring",
    jar = "@com_google_cloud_google_cloud_monitoring//jar:file",
    tags = ["manual"],
    runtime_deps = [
    ],
    deps = [
        "//third_party/com/google/api/grpc:grpc_google_cloud_monitoring_v3",
        "//third_party/com/google/cloud:google_cloud_core",
        "//third_party/io/grpc:grpc_auth",
        "//third_party/io/grpc:grpc_netty",
        "//third_party/io/grpc:grpc_stub",
        "//third_party/io/netty:netty_tcnative_boringssl_static",
    ],
)
