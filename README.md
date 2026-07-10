# intel-oneapi-github-actions
Use this template for all the Intel(R) oneAPI components inside your Github actions workflow file.

## Usage

```yml
- uses: neelravi/intel-oneapi-github-actions@latest
  with:
    components: 'fortran,cpp,mpi,mkl'
```

## Inputs

| Input | Required | Default value | Description |
| --- | --- | --- | --- |
| `components` | yes | `'fortran,cpp,mpi,mkl'` | Comma-separated list of Intel OneAPI components to install (e.g., fortran, cpp, mpi, mkl, basekit, hpckit) |

## Developer

@neelravi
Dr. Ravindra Shinde (neelravi@gmail.com)
