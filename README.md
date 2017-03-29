# Probot: DCO

a GitHub Integration built with [probot](https://github.com/probot/probot) that enforces the [Developer Certificate of Origin](https://developercertificate.org/) (DCO) on Pull Requests. It requires all commit messages to contain the `Signed-off-by` line with an email address that matches the commit author.

## Usage

[Configure the integration](https://github.com/integration/dco) for your organization or repositories. Enable [required status checks](docs/required-statuses.md) if you want to enforce the DCO on all commits.

Your contribution information (e.g., `CONTRIBUTING.md`) should document your use of the DCO and its relation to the `Signed-off-by` line. The DCO was developed for the Linux kernel; see its [submitting patches documentation](https://github.com/torvalds/linux/blob/master/Documentation/process/submitting-patches.rst#11-sign-your-work--the-developers-certificate-of-origin) for an example.
