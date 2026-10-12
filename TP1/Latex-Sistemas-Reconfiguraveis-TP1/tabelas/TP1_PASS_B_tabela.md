# PASS_B (op_sel = 0000)

Flags na ordem de `flags_out[4..0]` = C H Z V N. Valores lidos do waveform; cada caso dura 100 ns.

| Caso | Tempo (ns) | a_in | b_in | c_in | r_out | C | H | Z | V | N |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0-100 | FF | A5 | 0 | A5 | 0 | 0 | 0 | 0 | 1 |
| 2 | 100-200 | FF | 00 | 1 | 00 | 0 | 0 | 1 | 0 | 0 |
| 3 | 200-300 | 12 | 7F | 0 | 7F | 0 | 0 | 0 | 1 | 0 |
| 4 | 300-400 | 55 | 80 | 1 | 80 | 0 | 0 | 0 | 0 | 1 |
| 5 | 400-500 | 00 | FF | 0 | FF | 0 | 0 | 0 | 0 | 1 |
| 6 | 500-600 | F0 | 01 | 1 | 01 | 0 | 0 | 0 | 0 | 0 |
