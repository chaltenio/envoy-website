load("@rules_pkg//pkg:mappings.bzl", "pkg_filegroup", "pkg_files")
load("@rules_pkg//pkg:pkg.bzl", "pkg_tar")

pkg_files(
    name = "js",
    srcs = ["@com_github_twbs_bootstrap//:dist/js/bootstrap.bundle.min.js"],
    prefix = "theme/js",
    visibility = ["//visibility:public"],
)
