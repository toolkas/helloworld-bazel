java_library(
    name = "helloworld-lib",
    srcs = glob(["src/main/java/com/blogspot/toolkas/bazel/HelloWorld.java"]),
)

java_binary(
    name = "helloworld",
    main_class = "com.blogspot.toolkas.bazel.HelloWorld",
    runtime_deps = [":helloworld-lib"],
)