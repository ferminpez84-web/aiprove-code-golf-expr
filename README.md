# code-golf-expr

Entry: satu file `index.js` (373 byte), `module.exports = { evalExpr }`.

`evalExpr(s)` mengevaluasi ekspresi aritmetika: operator `+ - * /`, literal
integer/desimal, kurung, precedence normal. Mendukung spasi dan unary minus.
Parser recursive descent asli (tanpa `eval`/`Function`).

Uji: `node -e` terhadap 9 kasus publik + 20 kasus tambahan — 29/29 lulus
(lihat `test-results.md`).
