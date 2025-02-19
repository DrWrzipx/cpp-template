load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_test")

cc_test(
    name = "assert_vs_expect",
    srcs = ["assert_vs_expect.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "fib_test",
    srcs = ["fib_test.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "predicate",
    srcs = ["predicate.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "simple_assertions",
    srcs = ["simple_assertions.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "exceptions",
    srcs = ["exceptions.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "floating_points",
    srcs = ["floating_points.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "disabled_tests",
    srcs = ["disabled_tests.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "c_string_assertions",
    srcs = ["c_string_assertions.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_library(
    name = "prime_table",
    srcs = [
        "prime_table.cc",
    ],
    hdrs = ["prime_table.h"],
)

cc_test(
    name = "typed_tests",
    srcs = ["typed_tests.cc"],
    deps = [
        ":prime_table",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "private_members",
    srcs = ["private_members.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "filtered_tests",
    srcs = ["filtered_tests.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "typed_tests_findmax",
    srcs = ["typed_tests_findmax.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "death_test",
    srcs = ["death_test.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "propagating_failiures",
    srcs = ["propagating_failiures.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "cpplib_test",
    srcs = ["cpplib_test.cc"],
    deps = [
        "//src/lib:CPPLib",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test",
    srcs = ["sort_test.cc"],
    deps = [
        "//src/lib/sort:SortLib",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "search_test",
    srcs = ["search_test.cc"],
    deps = [
        "//src/lib/search:SearchLib",
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "test_fixture",
    srcs = ["test_fixture.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "gmock",
    srcs = ["gmock.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "gmock2",
    srcs = ["gmock2.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "findmax_test",
    srcs = ["findmax_test.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "hello_world_test",
    srcs = ["hello_world_test.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_binary(
    name = "hello_world_test_main",
    srcs = ["hello_world_test_main.cc"],
    deps = [
        "@com_google_googletest//:gtest",
    ],
)

cc_test(
    name = "sort_test_function",
    srcs = ["sort_test_function.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "test_fixture_shared_resources",
    srcs = ["test_fixture_shared_resources.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test_function_test_param",
    srcs = ["sort_test_function_test_param.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test_function_share_test_logic",
    srcs = ["sort_test_function_share_test_logic.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test_function_test_param_share_logic",
    srcs = ["sort_test_function_test_param_share_logic.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "user_types",
    srcs = ["user_types.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_binary(
    name = "fib_test_no_gtest",
    srcs = ["fib_test_no_gtest.cc"],
)

cc_test(
    name = "adding_traces",
    srcs = ["adding_traces.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "disabled_tests_fixture",
    srcs = ["disabled_tests_fixture.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test_function_test_param_share_logic_name_generator",
    srcs = ["sort_test_function_test_param_share_logic_name_generator.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)

cc_test(
    name = "sort_test_function_test_param_name_generator",
    srcs = ["sort_test_function_test_param_name_generator.cc"],
    deps = [
        "@com_google_googletest//:gtest_main",
    ],
)
