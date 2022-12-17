simple_text_viewer_sources = [
  'main.c',
  'simple-text-viewer-application.c',
  'simple-text-viewer-window.c',
]

simple_text_viewer_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1'),
]

simple_text_viewer_sources += gnome.compile_resources('simple-text-viewer-resources',
  'simple-text-viewer.gresource.xml',
  c_name: 'simple_text_viewer'
)

executable('simple-text-viewer', simple_text_viewer_sources,
  dependencies: simple_text_viewer_deps,
       install: true,
)
