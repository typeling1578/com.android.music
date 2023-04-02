android_library(
    name = "IMediaPlaybackService",
    idl_srcs = ["src/com/android/music/IMediaPlaybackService.aidl"],
)

android_binary(
    name = "Music",
    srcs = glob(["src/**/*.java"]),
    custom_package = "com.android.music",
    manifest = "AndroidManifest.xml",
    resource_files = glob(["res/**"]),
    deps = [":IMediaPlaybackService"],
)
