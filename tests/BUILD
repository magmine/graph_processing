load("@rules_cc//cc:defs.bzl", "cc_test")

cc_test(
    name = "algorithmsLib_test",
    srcs = ["algorithmsLib_test.cpp"],
    deps = [
        "//src/lib/algorithms:algorithmsLib",
        "//src/lib/loader:loaderLib",
        "@com_google_googletest//:gtest_main",
    ],
    data = ["//resources"],
)

cc_test(
    name = "graphLib_test",
    srcs = ["graphLib_test.cpp"],
    deps = [
        "//src/lib/graph:graphLib",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "loaderLib_test",
    srcs = ["loaderLib_test.cpp"],
    deps = [
        "//src/lib/loader:loaderLib",
        "@com_google_googletest//:gtest_main",
    ],
    data = ["//resources"],
)
