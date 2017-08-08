<h1 align="center">
  <img src="images/high_def_all4.png" alt="clusterProt" />
</h1>

# clusterProt
A Python script to analyze clustering of membrane proteins.

## Table of content

- [Description](#description)
- [Requirements](#requirements)
- [Example usage](#example-usage)
    - [Structure](#strucute)
    - [Trajectory](#trajectory)
- [Notes](#notes)
    - [Identifying bilayer leaflets](#identifying-bilayer-leaflets)
    - [Dealing with flip-flopping lipids](#dealing-with-flip-flopping-lipids)
    - [Specifying "protein" particles](#specifying-"protein"-particles)
    - [Detecting transmembrane clusters](#detecting-transmembrane-clusters)
    - [Specifying size groups](#specifying-size-groups)
    - [Visualizing results](#visualizing-results)
- [License](#license)
- [Troubleshooting](#troubleshooting)

## Description
This script calculates the evolution of proteins clustering status. It can produce 3 types of output:

### inputs
topology gromacs trajectory

### outputs
1. 2D plots: time evolution of the cluster size each protein is involved in
2. 1D plots: time evolution of the % of protein represented by each group
3. stability statistics: maximum number of consecutive frames each group existed for [TO DO]

## Requirements
* networkX
* sklearn
* MDAnalysis
* matplotlib

## Example-usage
### Structure
### trajectory
![2D](./doc/clusterProt2D.png)
 
```python
clusterProt -f file.gro -x file.xtc --leaflets
```

## Notes

### Identifying bilayer leaflets

### Dealing with flip-flopping lipids

### Specifying "protein" particles

### Detecting transmembrane clusters

### Specifying size groups

### Visualizing results

## License

## Troubleshooting

 
