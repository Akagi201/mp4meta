project(mp4meta)

set(SOURCE_FILES mp4meta.c)

include_directories("/usr/local/include")

link_directories("/usr/local/lib")

add_executable(mp4meta ${SOURCE_FILES})
