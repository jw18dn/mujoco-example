workspace(name = "mujoco_test")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "mujoco",
    commit = "a0a83f3b6874c149be9be5e1eaea7ebd0d4f2776",
    remote = "https://github.com/jeh15/mujoco_bazel.git",
)

load("@mujoco//:deps.bzl", "mujoco_deps")

mujoco_deps()