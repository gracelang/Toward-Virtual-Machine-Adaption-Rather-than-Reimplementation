sliverbeast8:SOMns kjx$ ./som -G core-lib/Benchmarks/Harness.som Sieve 10 0 10000
Sieve: iterations=1 runtime: 11757451us
Sieve: iterations=1 runtime: 11176885us
Sieve: iterations=1 runtime: 11720175us
Sieve: iterations=1 runtime: 15112788us
Sieve: iterations=1 runtime: 11433610us
Sieve: iterations=1 runtime: 11191896us
Sieve: iterations=1 runtime: 11172584us
Sieve: iterations=1 runtime: 11843087us
Sieve: iterations=1 runtime: 15160226us
Sieve: iterations=1 runtime: 11682471us
Sieve: iterations=10 average: 12225117us total: 122251173us
12s

sliverbeast8:SOMns kjx$ ./som core-lib/Benchmarks/Harness.som Sieve 10 0 10000
Sieve: iterations=1 runtime: 4931015us
Sieve: iterations=1 runtime: 571684us
Sieve: iterations=1 runtime: 774659us
Sieve: iterations=1 runtime: 557691us
Sieve: iterations=1 runtime: 375139us
Sieve: iterations=1 runtime: 298408us
Sieve: iterations=1 runtime: 285133us
Sieve: iterations=1 runtime: 368435us
Sieve: iterations=1 runtime: 289440us
Sieve: iterations=1 runtime: 284023us
Sieve: iterations=10 average: 873562us total: 8735627us
0.8s

sliverbeast8:SOMns kjx$ ./som  -G richard/GHarness.som Sieve 10 0 10000
Sieve: iterations=1 runtime: 77507701us
Sieve: iterations=1 runtime: 85228006us
Sieve: iterations=1 runtime: 89231568us
Sieve: iterations=1 runtime: 82423123us
Sieve: iterations=1 runtime: 81835338us
Sieve: iterations=1 runtime: 82852295us
Sieve: iterations=1 runtime: 80170332us
Sieve: iterations=1 runtime: 79183377us
Sieve: iterations=1 runtime: 80959236us
Sieve: iterations=1 runtime: 80398667us
Sieve: iterations=10 average: 81978964us total: 819789643us
81s

sliverbeast8:SOMns kjx$ ./som  richard/GHarness.som Sieve 10 0 10000
Sieve: iterations=1 runtime: 4549400us
Sieve: iterations=1 runtime: 531936us
Sieve: iterations=1 runtime: 417704us
Sieve: iterations=1 runtime: 726888us
Sieve: iterations=1 runtime: 706200us
Sieve: iterations=1 runtime: 917220us
Sieve: iterations=1 runtime: 581953us
Sieve: iterations=1 runtime: 429193us
Sieve: iterations=1 runtime: 472773us
Sieve: iterations=1 runtime: 440732us
Sieve: iterations=10 average: 977399us total: 9773999us
0.9s







sliverbeast8:SOMns kjx$ ./som -G core-lib/Benchmarks/Harness.som BlockRepeatF 10 0 10
BlockRepeatF: iterations=1 runtime: 2438459us
BlockRepeatF: iterations=1 runtime: 1967764us
BlockRepeatF: iterations=1 runtime: 1622779us
BlockRepeatF: iterations=1 runtime: 1828356us
BlockRepeatF: iterations=1 runtime: 1977968us
BlockRepeatF: iterations=1 runtime: 1880665us
BlockRepeatF: iterations=1 runtime: 1880307us
BlockRepeatF: iterations=1 runtime: 1891781us
BlockRepeatF: iterations=1 runtime: 2001008us
BlockRepeatF: iterations=1 runtime: 1562375us
BlockRepeatF: iterations=10 average: 1905146us total: 19051462us
1.9s

sliverbeast8:SOMns kjx$ ./som core-lib/Benchmarks/Harness.som BlockRepeatF 10 0 10
BlockRepeatF: iterations=1 runtime: 1984383us
BlockRepeatF: iterations=1 runtime: 13296us
BlockRepeatF: iterations=1 runtime: 13671us
BlockRepeatF: iterations=1 runtime: 14847us
BlockRepeatF: iterations=1 runtime: 19323us
BlockRepeatF: iterations=1 runtime: 28097us
BlockRepeatF: iterations=1 runtime: 14046us
BlockRepeatF: iterations=1 runtime: 12509us
BlockRepeatF: iterations=1 runtime: 15842us
BlockRepeatF: iterations=1 runtime: 15547us
BlockRepeatF: iterations=10 average: 213156us total: 2131561us
0.21s

sliverbeast8:SOMns kjx$ ./som  -G richard/GHarness.som SumMillion 10 0 10
SumMillion: iterations=1 runtime: 1934533us
SumMillion: iterations=1 runtime: 1462750us
SumMillion: iterations=1 runtime: 1340592us
SumMillion: iterations=1 runtime: 1345945us
SumMillion: iterations=1 runtime: 1505779us
SumMillion: iterations=1 runtime: 1922145us
SumMillion: iterations=1 runtime: 1789388us
SumMillion: iterations=1 runtime: 1731200us
SumMillion: iterations=1 runtime: 1864769us
SumMillion: iterations=1 runtime: 1891555us
SumMillion: iterations=10 average: 1678865us total: 16788656us
1.7s

sliverbeast8:SOMns kjx$ ./som  richard/GHarness.som SumMillion 10 0 10
SumMillion: iterations=1 runtime: 2040309us
SumMillion: iterations=1 runtime: 45266us
SumMillion: iterations=1 runtime: 33278us
SumMillion: iterations=1 runtime: 38322us
SumMillion: iterations=1 runtime: 36705us
SumMillion: iterations=1 runtime: 29065us
SumMillion: iterations=1 runtime: 42351us
SumMillion: iterations=1 runtime: 28856us
SumMillion: iterations=1 runtime: 36263us
SumMillion: iterations=1 runtime: 30981us
SumMillion: iterations=10 average: 236139us total: 2361396us
0.24s




sliverbeast8:SOMns kjx$ ./som -G core-lib/Benchmarks/Harness.som  Mandelbrot 10 0 500
Mandelbrot: iterations=1 runtime: 4014419us
Mandelbrot: iterations=1 runtime: 4759086us
Mandelbrot: iterations=1 runtime: 5262139us
Mandelbrot: iterations=1 runtime: 4624475us
Mandelbrot: iterations=1 runtime: 3935942us
Mandelbrot: iterations=1 runtime: 3320776us
Mandelbrot: iterations=1 runtime: 3872845us
Mandelbrot: iterations=1 runtime: 4292335us
Mandelbrot: iterations=1 runtime: 4539641us
Mandelbrot: iterations=1 runtime: 4341726us
Mandelbrot: iterations=10 average: 4296338us total: 42963384us
4.3s

sliverbeast8:SOMns kjx$ ./som core-lib/Benchmarks/Harness.som  Mandelbrot 10 0 500
Mandelbrot: iterations=1 runtime: 3600794us
Mandelbrot: iterations=1 runtime: 3827884us
Mandelbrot: iterations=1 runtime: 5506489us
Mandelbrot: iterations=1 runtime: 63713us
Mandelbrot: iterations=1 runtime: 64425us
Mandelbrot: iterations=1 runtime: 71116us
Mandelbrot: iterations=1 runtime: 63909us
Mandelbrot: iterations=1 runtime: 67472us
Mandelbrot: iterations=1 runtime: 58105us
Mandelbrot: iterations=1 runtime: 63721us
Mandelbrot: iterations=10 average: 1338762us total: 13387628us
1.3s

sliverbeast8:SOMns kjx$ ./som -G richard/GHarness.som  Mandelbrot 10 0 500
Mandelbrot: iterations=1 runtime: 14380076us
Mandelbrot: iterations=1 runtime: 13601404us
Mandelbrot: iterations=1 runtime: 11436708us
Mandelbrot: iterations=1 runtime: 11231477us
Mandelbrot: iterations=1 runtime: 11101348us
Mandelbrot: iterations=1 runtime: 10431940us
Mandelbrot: iterations=1 runtime: 13139888us
Mandelbrot: iterations=1 runtime: 17005134us
Mandelbrot: iterations=1 runtime: 18901456us
Mandelbrot: iterations=1 runtime: 13222316us
Mandelbrot: iterations=10 average: 13445174us total: 134451747us
13s

sliverbeast8:SOMns kjx$ ./som richard/GHarness.som  Mandelbrot 10 0 500
Mandelbrot: iterations=1 runtime: 8864688us
Mandelbrot: iterations=1 runtime: 2874122us
Mandelbrot: iterations=1 runtime: 2552433us
Mandelbrot: iterations=1 runtime: 2053976us
Mandelbrot: iterations=1 runtime: 376553us
Mandelbrot: iterations=1 runtime: 364679us
Mandelbrot: iterations=1 runtime: 494922us
Mandelbrot: iterations=1 runtime: 340921us
Mandelbrot: iterations=1 runtime: 355371us
Mandelbrot: iterations=1 runtime: 320533us
Mandelbrot: iterations=10 average: 1859819us total: 18598198us
1.9s