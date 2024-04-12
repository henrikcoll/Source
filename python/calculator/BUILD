py_library(
    name = "calculator",
    srcs = ["calculator.py"],
    visibility = ["//python/calculator_web:__pkg__"],
)

py_test(
    name = "calculator_test",
    srcs = ["calculator_test.py"],
    deps = ["//python/calculator:calculator"],
    timeout = "short"
)
