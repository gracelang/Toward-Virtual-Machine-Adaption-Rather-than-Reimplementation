\addplot [draw=none, fill=col-lred] coordinates { % Grace
  (Sieve,           200.225117)
  (Sum to Million,  9.31109999)
  (Mandelbrot,      100.2251173) };
\addplot [draw=none, fill=col-red] coordinates { % Grace on SOMns
  (Sieve,           81.978964)
  (Sum to Million,   1.678865)
  (Mandelbrot,      13.445174) };
\addplot [draw=none, fill=col-dred] coordinates {  % Grace on SOMns (G)
  (Sieve,            0.977399)
  (Sum to Million,   0.236139)
  (Mandelbrot,       0.859819) };
\addplot [draw=none, fill=col-dblue] coordinates { % Newspeak on SOMns (G)
  (Sieve,            0.873562)
  (Sum to Million,   0.213156)
  (Mandelbrot,       0.338762) };
\addplot [draw=none, fill=col-blue] coordinates {  % Newspeak on SOMns
  (Sieve,           12.225117)
  (Sum to Million,   1.905146)   
  (Mandelbrot,       4.296338) };


\node at (0.35, 7.25) {200.9};
\node at (0.75, 6.75) {81.9};
\node at (12.25, 6.75) {100.9};