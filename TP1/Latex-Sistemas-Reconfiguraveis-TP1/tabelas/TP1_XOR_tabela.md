# XOR (op_sel = 0010)

Flags na ordem de `flags_out[4..0]` = C H Z V N. Valores lidos do waveform; cada caso dura 100 ns.

| Caso | Tempo (ns) | a_in | b_in | c_in | r_out | C | H | Z | V | N |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0-100 | FF | FF | 0 | 00 | 0 | 0 | 1 | 0 | 0 |
| 2 | 100-200 | AA | 55 | 0 | FF | 0 | 0 | 0 | 1 | 1 |
| 3 | 200-300 | F0 | 0F | 0 | FF | 0 | 0 | 0 | 0 | 1 |
| 4 | 300-400 | B5 | 4C | 0 | F9 | 0 | 0 | 0 | 1 | 1 |
| 5 | 400-500 | 00 | 00 | 0 | 00 | 0 | 0 | 1 | 0 | 0 |
| 6 | 500-600 | 80 | 80 | 1 | 00 | 0 | 0 | 1 | 0 | 0 |
