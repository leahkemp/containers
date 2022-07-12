# Recipes for containerised software

Naming convention for recipe files:

- Singularity or docker container
- Software name
- Version

To build singularity container from a singularity recipe file:

```bash
mkdir -p images
sudo singularity build images/singularity.parallel.20220522.sif recipes/singularity.parallel.20220522
```

