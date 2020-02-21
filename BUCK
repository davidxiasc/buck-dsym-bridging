apple_binary(
  name = 'Test',
  srcs = glob([
    'Source/**/*.m',
    'Source/**/*.swift',
  ]),
  headers = glob([
    'Source/**/*.h'
  ]) + [
    'SameDirectory.h',
  ],
  bridging_header = 'Bridging-Header.h',
  swift_version = '5',
)
