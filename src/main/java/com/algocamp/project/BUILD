
java_library(
    name = "util_lib",
    srcs = glob(["src/main/java/com/algocamp/project/utils/*.java"]),
    visibility = ["//visibility:public"],
)
java_binary(
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.algocamp.project.HelloWorld",
    name = "hello_world",
    runtime_deps = [
        ":util_lib"
    ],
)
