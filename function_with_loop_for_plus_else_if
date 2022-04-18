function calculaGostos (notas) {
  var nNaoGostaram = 0;
  var nMediano = 0;
  var nGostaram = 0;
  for (var i = 0 ; i < notas.length ; i++) {
      if (notas[i] >= 0 && notas[i] < 2) {
          nNaoGostaram++;
          } 
      else if(notas[i] >= 2 && notas[i] < 4) {
          nMediano++;
      } else {
          nGostaram++;
      }
  }
  return [nNaoGostaram, nMediano, nGostaram];
}
