
java_library(
    name = "util_lib",
    srcs = glob(["utils/*.java"]),
    visibility = ["//visibility:public"],
)
java_binary(
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.algocamp.project.HelloWorld",
    name = "hello_world",
    deps = [
        ":util_lib"
    ],
)
