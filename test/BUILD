cc_test(
    name = "codesearch_test",
    srcs = [ "codesearch_test.cc" ],
    deps = [
        "@gtest//:main",
        "//src:codesearch",
      "@com_github_libgit2//:libgit2",
    ],
    defines = [
        "GTEST_HAS_TR1_TUPLE",
        "GTEST_USE_OWN_TR1_TUPLE=0",
    ],
    size = "small",
)
