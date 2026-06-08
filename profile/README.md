[![Mirror banner](./banner.svg)](https://gitlab.com/ocudu)

# The OCUDU Project

<img src="https://srs.io/wp-content/uploads/ocudu_color.png" alt="image" width="50%"/>

OCUDU is a permissively-licensed, open-source 5G (and beyond) CU/DU project designed for commercial deployment and broad industry adoption, as well as advanced research and development.
OCUDU is a complete RAN solution compliant with 3GPP and O-RAN Alliance specifications and includes the full L1/2/3 stack with minimal external dependencies.
OCUDU is governed under the [Linux Foundation](https://ocudu.org/).

For general information, visit <https://ocudu.org>.

## Contributing

Our project welcomes contributions from any member of our community. To get started contributing,
please take a look at the [CONTRIBUTING.md](https://gitlab.com/ocudu/ocudu/-/blob/dev/CONTRIBUTING.md?ref_type=heads) or
check the [Developer Guide](https://docs.ocudu.org/dev_guide/contributing_guide/) with detailed instructions on how to best engange with us.

Any contribution requiring a patent license beyond what is already required under relevant 3GPP standards must be disclosed with the contribution.
Contributions requiring additional license requirements must be approved by the TSC committee or a designated subcommittee of the TSC prior to acceptance into any OCUDU codebase.

## Governance

The OCUDU project is governed by a framework of principles, values, policies and processes to help our community and constituents towards our shared goals.
The [Governance](https://gitlab.com/ocudu/Governance) repo is used by the Technical Steering Committee, which oversees governance of the project.

## Github Organization Structure

This Github Organization contains multiple git repositories. Main ones are:

| Repository | Description |
|---|---|
| [ocudu](https://github.com/ocudu/ocudu) | Full 5G L1/2/3 CU-DU stack (Main repo) |
| [ocudu_docs](https://github.com/ocudu/ocudu_docs) | Documentation site |
| [ocudu_infra_srs](https://github.com/ocudu/ocudu_infra_srs) | E2E tests, Test Framework, CI and IaC |
| [ocudu-matlab](https://github.com/ocudu/ocudu-matlab) | MATLAB tools for PHY benchmarking and test-vector generation |
| [ocudu_test_report](https://github.com/ocudu/ocudu_test_report) | Unified test reports and feature tracking |
| [ocudu_o1_adapter](https://github.com/ocudu/ocudu_o1_adapter) | Adapter between CU/DU towards the Service Management and Orchestration (SMO) |

## License

This project is licensed under the BSD 3-Clause Open MPI variant License.
Portions of this software may implement 3GPP specifications, which may be subject to additional licensing requirements.
