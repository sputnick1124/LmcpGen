srcs_lmcp = [
  'avtas/lmcp/ByteBuffer.cpp',
  'avtas/lmcp/Factory.cpp',
  'avtas/lmcp/Node.cpp',
  'avtas/lmcp/NodeUtil.cpp',
  'avtas/lmcp/XMLParser.cpp',
  -<meson_source_list>-]

incs_lmcp = include_directories('.')

lib_lmcp = static_library(
  'lmcp',
  srcs_lmcp,
  cpp_args: [
    '-std=c++11',
    '-Wall',
  ],
  include_directories: incs_lmcp,
)
