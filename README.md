# ProjectMirador
patched mirador 2.5.0 instance to allow for canvas level metadata display in info panel



hints:
patched lines should be limited to two sections
:40503
added function
......updateCanvasInfo: function(manifestJson,canvasJson) {

:40561
......_this.updateCanvasInfo(this.manifest.jsonLd, this.canvasJson);
  
  
  included in repo is patch file as well as implemented patch
  
  TODO: add precompiled source