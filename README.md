# gha-download-and-extract-artifact

GitHub Action used as a workaround for GHES multi-file artifact slowdown after
using gha-package-and-upload-artifact - Downloads via actions/download-artifact
and extracts artifacts. 

## Usage

```yaml
steps:
  - name: Download and Extract Artifact
    uses: albr21/gha-download-and-extract-artifact@1.0.0
    with:
      path: /path/to/extract
      artifact-id: my-artifact
      package-name: my-package
```

## Contributing

Check out the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
