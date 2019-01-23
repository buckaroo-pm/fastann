cxx_library(
  name = 'fastann',
  srcs = glob(
    ['*.cpp', '*.c'], 
    exclude=glob(['test*.cpp', 'perf*.cpp'])),
  exported_headers = glob(['*.h', '*.hpp']),
  visibility = ['PUBLIC']
)

cxx_binary(
  name = 'test',
  srcs = ['test_dist_l2.cpp'],
  deps = [':fastann']
)
