# Description:
# A plugin system for TensorBoard

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])

py_library(
    name = "base_plugin",
    srcs = ["base_plugin.py"],
    srcs_version = "PY3",
    visibility = ["//visibility:public"],
    deps = [
        "@org_pythonhosted_six",
    ],
)

py_test(
    name = "base_plugin_test",
    srcs = ["base_plugin_test.py"],
    srcs_version = "PY3",
    deps = [
        ":base_plugin",
        "//tensorboard:test",
        "@org_pythonhosted_six",
    ],
)
