include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-ptr-container', 
  header_only = True,
  header_namespace = 'boost/ptr_container',
  exported_headers = subdir_glob([
    ('include/boost/ptr_container', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
