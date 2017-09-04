include_defs('//BUCKAROO_DEPS')

java_library(
  name = 'lib',
  srcs = [
    'App.java',
  ],
  deps = BUCKAROO_DEPS,
)

java_binary(
  name = 'app',
  main_class = 'App',
  deps = [
    ':lib',
  ],
)
