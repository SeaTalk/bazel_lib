package(default_visibility = ["//visibility:public"],)

licenses(["notice"])  # Apache 2.0

# libs

cc_library(
    name = "boost",
    hdrs = glob([
        "boost/include/**/*.hpp",
        "boost/include/**/*.h",
	"boost/include/**/*.ipp",
    ]),
    srcs = glob(["boost/lib/**/*.a",]),
    includes = ["boost/include",],
    deps = [":zlib", ":iconv"],
    visibility = ["//visibility:public",],
)

cc_library(
    name = "boost_lexical_cast",
    hdrs = glob([
        "boost/include/boost/lexical_cast.hpp",
        "boost/include/boost/lexical_cast/**/*.hpp",
    ]),
    includes = ["boost/include",],
    visibility = ["//visibility:public",],
)

cc_library(
    name = "boost_string_algo",
    hdrs = glob([
        "boost/include/boost/algorithm/string.hpp",
        "boost/include/boost/algorithm/string/**/*.hpp",
    ]),
    includes = ["boost/include",],
    visibility = ["//visibility:public",],
)

cc_library(
    name = "boost_filesystem",
    hdrs = glob([
        "boost/include/boost/filesystem.hpp",
        "boost/include/boost/filesystem/**/*.hpp",
    ]),
    includes = ["boost/include",],
    srcs = glob([
        "boost/lib/libboost_filesystem.a",
        "boost/lib/libboost_system.a",
    ]),
    visibility = ["//visibility:public",],
)

cc_library(
    name = "boost_thread",
    hdrs = glob([
        "boost/include/boost/thread.hpp",
        "boost/include/boost/thread/**/*.hpp",
        "boost/include/boost/system/**/*.hpp",
    ]),
    includes = ["boost/include",],
    srcs = glob([
        "boost/lib/libboost_thread.a",
        "boost/lib/libboost_system.a",
    ]),
    visibility = ["//visibility:public",],
)

cc_library(
    name = "boost_locale",
    hdrs = glob([
        "boost/include/boost/locale.hpp",
        "boost/include/boost/locale/**/*.hpp",
    ]),
    includes = ["boost/include",],
    srcs = glob([
        "boost/lib/libboost_locale.a",
    ]),
    visibility = ["//visibility:public",],
)

