How to make libuv.framework for ios

  tar -zxvf libuv-v1.7.5.tar.gz

  mkdir libuv-v1.7.5/uv.xcodeproj

  cp patch/project.pbxproj.ios libuv-v1.7.5/uv.xcodeproj/project.pbxproj

  enter libuv-v1.7.5

  open uv.xcodeproj

  ...

