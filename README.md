# EthiX: A Dataset for Argument Scheme Classification in Ethical Debates

EthiX contains 686 arguments from 22 ethical debates on [Kialo](https://www.kialo.com), each annotated with one of eight argument schemes from Walton's taxonomy. It was introduced in our ECAI 2024 paper (see [Citation](#citation)).

## Files

| File | Contents |
|---|---|
| `Dataset.csv` | One argument per row. Columns: `Argument` (the argument text), `Debate` (the debate question it belongs to), `Scheme` (label 0–7) |
| `label_descriptions.txt` | The eight argument schemes and their labels |

## Labels

| Label | Argument scheme | Arguments |
|---|---|---|
| 0 | Argument from example | 119 |
| 1 | Argument from values | 117 |
| 2 | Argument from positive consequences | 97 |
| 3 | Argument from cause to effect | 88 |
| 4 | Argument from expert opinion | 81 |
| 5 | Argument from negative consequences | 78 |
| 6 | Argument from alternatives | 56 |
| 7 | Argument from analogy | 50 |

## Citation

If you use EthiX, please cite:

```bibtex
@inproceedings{bezouvrakatseli2024ethix,
  title     = {{EthiX}: A Dataset for Argument Scheme Classification in Ethical Debates},
  author    = {Bezou-Vrakatseli, Elfia and Cocarascu, Oana and Modgil, Sanjay},
  booktitle = {Proceedings of the 27th European Conference on Artificial Intelligence (ECAI 2024)},
  pages     = {3628--3635},
  year      = {2024}
}
```

## License

EthiX is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may use and adapt it for non-commercial purposes, including research and teaching, provided you cite the paper above and share any adaptations under the same license. See [`LICENSE`](LICENSE) for details.

**Kialo content.** The argument and debate texts were written by Kialo users and collected from public debates on kialo.com. We do not own this text, and its use is also subject to [Kialo's Terms of Service](https://www.kialo.com/terms). Our license covers our own contributions: the selection of arguments, the scheme annotations and the label descriptions.

## Contact

Elfia Bezou-Vrakatseli — elfia.bezou_vrakatseli@kcl.ac.uk
