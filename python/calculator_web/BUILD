load("@pip//:requirements.bzl", "requirement")

py_library(
    name = "calculator_web_lib",
    srcs = ["main.py"],
    deps = [
        requirement("Flask"),
        "//python/calculator:calculator",
    ],
)

py_binary(
    name = "calculator_web",
    srcs = ["main.py"],
    main = "main.py",
    deps = [":calculator_web_lib"],
)
