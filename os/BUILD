# Standard constraint_setting and constraint_values to be used in platforms.
licenses(["notice"])

package(
    default_visibility = ["//visibility:public"],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)

# To add a new constraint_value see https://github.com/bazelbuild/platforms.
constraint_setting(name = "os")

constraint_value(
    name = "osx",
    constraint_setting = ":os",
)

constraint_value(
    name = "ios",
    constraint_setting = ":os",
)

constraint_value(
    name = "freebsd",
    constraint_setting = ":os",
)

constraint_value(
    name = "android",
    constraint_setting = ":os",
)

constraint_value(
    name = "linux",
    constraint_setting = ":os",
)

constraint_value(
    name = "windows",
    constraint_setting = ":os",
)
