# e_plagio
sistema de plágio
javascript:(function(){
  _my_script=document.createElement('SCRIPT');
  _my_script.type='text/javascript';
  _my_script.src='http://10.0.255.54/Academico/Integracao/AntiPlagio/bookmarklet.js';
  document.getElementsByTagName('head')[0].appendChild(_my_script);

  setTimeout(function(){ Textar("TBControlV") }, 500);
})();
