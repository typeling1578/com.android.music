android_binary(
    name = "Music",
    srcs = glob(["src/**/*.java"]),
    custom_package = "com.android.music",
    manifest = "AndroidManifest.xml",
    # TODO(b/179889880): this manual BUILD file exists because these resources,
    # if listed as files, would cross package boundary.
    resource_files = ["//kotlin:MusicResourceFiles"],
)
