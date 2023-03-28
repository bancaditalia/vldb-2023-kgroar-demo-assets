# VLDB 2023 submission — KG-Roar 🦁 demo assets

This repository Datasets used for the paper "KG-Roar: Interactive Datalog-based Reasoning on Virtual Knowledge Graphs" submitted to [VLDB 2023](https://vldb.org/2023/), the 49th International Conference on Very Large Data Bases.

# Datasets

These synthetic datasets have been used for an experimental evaluation of the elapsed time for company control reasoning task with growing graph size.

## Folder structure

```bash
repo
┣━ synthetic_graphs:
┃  ┗━ parquet: size_<n>M_nodes.parquet
┃  ┗━ csv: size_<n>M_nodes.parquet
┗━ synthetic_targets:
   ┗━ parquet: sampling_from_<n>M_generation_<g>_size_<m>.parquet
   ┗━ csv: sampling_from_<n>M_generation_<g>_size_<m>.parquet
```

## Dataset description

`synthetic_graphs` are ...; the naming convention specifies the number `n` of...

`synthetic_targets` are ...; the naming convention specifies:
* the number `n` of ...;
* the generation `g` that ...;
* the size `m` of ....


## Authors
* Luigi Bellomarini, [Bank of Italy](https://www.bankit.art/people/luigi-bellomarini)
* Marco Benedetti, [Bank of Italy](https://www.bankit.art/people/marco-benedetti)
* Andrea Gentili, [Bank of Italy](https://www.bankit.art/people/andrea-gentili)
* Davide Magnanimi, [Bank of Italy](https://www.bankit.art/people/davide-magnanimi) & Politecnico di Milano
* Emanuel Sallinger, [TU Wien](https://www.dbai.tuwien.ac.at/staff/sallinger/) & [University of Oxford](https://www.cs.ox.ac.uk/people/emanuel.sallinger/)

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
