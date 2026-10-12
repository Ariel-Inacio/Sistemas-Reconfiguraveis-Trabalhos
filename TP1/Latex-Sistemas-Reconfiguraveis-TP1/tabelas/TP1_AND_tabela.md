# AND (op_sel = 0011)

Flags na ordem de `flags_out[4..0]` = C H Z V N. Valores lidos do waveform; cada caso dura 100 ns.

| Caso | Tempo (ns) | a_in | b_in | c_in | r_out | C | H | Z | V | N |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0-100 | 0F | F0 | 0 | 00 | 0 | 0 | 1 | 0 | 0 |
| 2 | 100-200 | FF | FF | 0 | FF | 0 | 0 | 0 | 0 | 1 |
| 3 | 200-300 | F0 | 3C | 0 | 30 | 0 | 0 | 0 | 0 | 0 |
| 4 | 300-400 | B5 | 4C | 0 | 04 | 0 | 0 | 0 | 1 | 0 |
| 5 | 400-500 | 80 | FF | 0 | 80 | 0 | 0 | 0 | 0 | 1 |
| 6 | 500-600 | 55 | AA | 1 | 00 | 0 | 0 | 1 | 1 | 0 |
