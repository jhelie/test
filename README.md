<h1 b align="center">clusterProt</b></h1>
<p align="center">A Python script to analyze clustering of membrane proteins.</p>
<h1 align="center">
  <img src="images/high_def_all4.png" alt="clusterProt" />
</h1>

## Table of content

- [**What it does**](#description)
  - [Protein population distribution](#pprotein-opulation-distribution)
  - [Intra-cluster interactions](#intra-cluster-interactions)  
  - [Cluster composition statistics](#cluster-composition-statistics)  
  - [Cluster size evolution](#cluster-size-evolution)  
  - [Cluster visualisation](#cluster-visualisation)  
- [**How to use it**](#how-to-use-it)
  - [Requirements](#requirements)
  - [Examples](#examples)
  - [License](#license)
- [**How it works**](#notes)
  - [Bilayer leaflets](#bilayer-leaflets)
  - [Flip-flopping lipids](#flip-flopping-lipids)
  - ["Protein" particles](#"protein"-particles)
  - [Transmembrane clusters](#transmembrane-clusters)
  - [Visualisation](#visualisation)
- [**Troubleshooting**](#troubleshooting)

## What it does
This script calculates the evolution of proteins clustering status. It can produce 3 types of output. Inputs = topology gromacs trajectory.
### Protein population distribution
### Intra-cluster interactions
### Cluster composition statistics
### Cluster size evolution
### Cluster visualisation

## How to use it
### Requirements
* networkX
* sklearn
* MDAnalysis
* matplotlib
### Examples

![2D](./doc/clusterProt2D.png) <!-- .element height="10%" width="10%" -->

```bash
clusterProt -f file.gro -x file.xtc --leaflets
```
### License
Free for... please cite...

## How it works
### Bilayer leaflets
### Flip-flopping lipids
### "Protein" particles
### Transmembrane clusters
### Visualisations

## Troubleshooting

 
