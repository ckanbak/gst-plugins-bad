videoframe_audiolevel_sources = [
  'gstvideoframe-audiolevel.c',
]

gstvideoframe_audiolevel = library('gstvideoframe_audiolevel',
  videoframe_audiolevel_sources,
  c_args : gst_plugins_bad_args,
  include_directories : [configinc],
  dependencies : [gstvideo_dep, gstaudio_dep, libm],
  install : true,
  install_dir : plugins_install_dir,
)
pkgconfig.generate(gstvideoframe_audiolevel, install_dir : plugins_pkgconfig_install_dir)
