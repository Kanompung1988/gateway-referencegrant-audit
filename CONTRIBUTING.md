# Contributing

Thanks for helping improve this standalone Agent Skill.

1. Open an issue describing an actual Gateway API ReferenceGrant mismatch with **sanitized** YAML, expected behavior and controller/version context.
2. Create a non-default branch and add a synthetic regression fixture/test to `tests/test_audit.py`. No real cluster credentials or secrets.
3. Run `python -m pip install 'PyYAML>=6,<7'`, `python -m unittest discover -s tests -v`, and both `examples/` fixtures.
4. Open a PR explaining the contract and limitations. Maintain 0/1/2 CLI exit conventions. Keep source read-only, offline, bounded and portable.
5. Do not change original Area Zero logos or imply the MIT license grants trademark rights.

Security issues: do not attach sensitive manifests; privately contact the maintainer before public disclosure.
