package(default_visibility = ["//src:__subpackages__"])

java_library(
    name = "testbed",
    testonly = 1,
    srcs = glob(["*.java"]),
    deps = [
        "//third_party:guava",
        "//third_party:junit4",
        "//third_party:truth",
    ],
)

exports_files([
    "XmlOutputExercises.ant.xml",
])

filegroup(
    name = "srcs",
    srcs = glob(["*.java"]) + [
        "BUILD",
        "XmlOutputExercises.ant.xml",
    ],
)
