# Standard cpu name constraint_setting and constraint_values
licenses(["notice"])

package(
    default_visibility = ["//visibility:public"],
)

filegroup(
    name = "srcs",
    srcs = glob(["**"]),
)

# To add a new constraint_value see https://github.com/bazelbuild/platforms.
constraint_setting(name = "cpu")

constraint_value(
    name = "x86_32",
    constraint_setting = ":cpu",
)

constraint_value(
    name = "x86_64",
    constraint_setting = ":cpu",
)

constraint_value(
    name = "ppc",
    constraint_setting = ":cpu",
)

constraint_value(
    name = "arm",
    constraint_setting = ":cpu",
)

constraint_value(
    name = "aarch64",
    constraint_setting = ":cpu",
)

constraint_value(
    name = "s390x",
    constraint_setting = ":cpu",
)
