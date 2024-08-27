# Long Genome Assembly

This is a Snakemake workflow for long read genome assembly.

## Installation

### Prerequisites

**Snakemake**: Ensure you have Snakemake installed. You can install it via conda:

```bash
conda install -c bioconda snakemake
```

### Clone the Repository

Clone this repository to your local machine:

```bash
git clone /github/link/myproject.git
cd myproject
```

## Usage

### `config.yaml`

Provide or update a `config.yaml` file, providing all the necessary parameters.

## Run workflow

```bash
snakemake --snakefile /path/to/Snakefile --configfile /path/to/configfile --software-deployment-method conda --cores 2
```
