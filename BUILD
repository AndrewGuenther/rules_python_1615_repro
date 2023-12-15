load("@rules_python//python:defs.bzl", "py_binary")
load("@pip//:requirements.bzl", "requirement")

py_binary(
  name = "hello_world",
  srcs = ["hello_world.py"],
  deps = [
    requirement("pyjwt"),
  ]
)
