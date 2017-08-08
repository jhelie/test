<h1 align="center">clusterProt</h1>
<h1 align="center">
  <img src="images/high_def_all4.png" alt="clusterProt" />
</h1>

A Python script to analyze clustering of membrane proteins.

## Table of content

- [**What it does**](#description)
  - [population distribution](#population-distribution)
  - [intra-cluster interactions](#intra-cluster-interactions)  
  - [cluster composition statistics](#cluster-composition-statistics)  
  - [cluster size evolution](#cluster-size-evolution)  
  - [cluster visualisation](#cluster-visualisation)  
- [**How to use it**](#how-to-use-it)
  - [Requirements](#requirements)
  - [Examples](#examples)
  - [License](#license)
- [**How it works**](#notes)
  - [Bilayer leaflets](#identifying-bilayer-leaflets)
  - [Flip-flopping lipids](#dealing-with-flip-flopping-lipids)
  - ["Protein" particles](#specifying-"protein"-particles)
  - [Transmembrane clusters](#detecting-transmembrane-clusters)
  - [Visualisation](#visualizing-results)
- [**Troubleshooting**](#troubleshooting)

## What it does
This script calculates the evolution of proteins clustering status. It can produce 3 types of output. Inputs = topology gromacs trajectory.

## population distribution
## intra-cluster interactions
## cluster composition statistics
## cluster size evolution
## cluster visualisation

## How to use it

### Requirements
* networkX
* sklearn
* MDAnalysis
* matplotlib

### Examples
![2D](./doc/clusterProt2D.png)
 
```bash
clusterProt -f file.gro -x file.xtc --leaflets
```

### License
Free for... please cite...

## How it works

### Identifying bilayer leaflets

### Dealing with flip-flopping lipids

### Specifying "protein" particles

### Detecting transmembrane clusters

### Specifying size groups

### Visualizing results


## Troubleshooting

 
