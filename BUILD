android_library(
    name = "IMediaPlaybackService",
    idl_srcs = ["app/src/main/java/com/android/music/IMediaPlaybackService.aidl"],
)

android_binary(
    name = "Music",
    srcs = glob(["app/src/main/java/**/*.java"]),
    custom_package = "com.android.music",
    manifest = "app/src/main/AndroidManifest.xml",
    resource_files = glob(["app/src/main/res/**"]),
    deps = [":IMediaPlaybackService"],
)
