use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '63394054b5afa14aee3e32bd12b227eb7225b871',
  'glslang_revision': 'f5d2960bbd08bcabe003eaf07a2569f897587d44',
  'googletest_revision': 'd72f9c8aea6817cdf1ca0ac10887f328de7f3da2',
  're2_revision': '972a15cedd008d846f1a39b2e88ce48d7f166cbd',
  'spirv_headers_revision': '465055f6c9128772e20082e893d974146acf7a02',
  'spirv_tools_revision': 'e4bceacf59fdfe742047e94e41ef65a48999a0dd',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
