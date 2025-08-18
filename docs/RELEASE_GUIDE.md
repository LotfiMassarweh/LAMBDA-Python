For a new release, follow these steps:
- Make sure all tests are passed [https://github.com/LotfiMassarweh/LAMBDA-Python/tree/main/tests]
- Change version number in pyproject.toml [https://github.com/LotfiMassarweh/LAMBDA-Python/blob/main/pyproject.toml]
- Update README.md of the repository with latest information on LAMBDA package
- Create release on GitHub, never choose pre-release (since does not publish on Pypi) [https://github.com/LotfiMassarweh/LAMBDA-Python/releases] + check option "Set as the latest release" 
- Check the Pypi GitHub action to see if successfull [https://github.com/LotfiMassarweh/LAMBDA-Python/actions/workflows/pypi.yml]
