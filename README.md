# AMAZING model

This is the source code for the AMAZING model. AMAZING is used to
classify handwritten digits from an obscure, little known dataset
known as MNIST. We expect that our work will inspire future
generations to train similar classifiers. Time will tell!

## Recreating our results

This project uses [Guild AI](https://guild.ai), the best and most
incredible experiment reproducibility tool in the history of the known
universe.

It uses the power of the command line.

[Install Guild AI first](https://guild.ai/install/).

### Step 1. Clone our repo

``` bash
$ git clone git@github.com:guildai/amazing-results-project
```

### Step 2. Change to the project directory

``` bash
$ cd amazing-results-project
```

### Step 3. Use Guild to reproduce the results

```bash
$ guild run
```

Once the models have trained, you can compare the results by running:

``` bash
$ guild compare
```
