Modify values.yaml if needed. Once done, run:
```
helm template xrootd . --values values.yaml &> produced.yaml
```
and `kubectl apply -f ...`
