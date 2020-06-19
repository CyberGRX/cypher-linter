# cypher-linter
Pre-commit hook that will run `cypher-lint` on `.cypher|.cql|.cpy` files. 

# usage
Add the following block to your `.pre-commit-config.yaml`
```
  - repo: https://github.com/CyberGRX/cypher-linter
    rev: master
    hooks:
      - id: cypher-linter
```
