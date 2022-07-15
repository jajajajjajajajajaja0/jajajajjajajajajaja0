//for (var i = 0; i < palavras.length; i++) {
for (var p of palavras) {
    p = p.toLowerCase();
    p = p[0].toUpperCase() + p.slice(1);
    console.log(p);
}
