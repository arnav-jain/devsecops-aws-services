This is a sample pipeline built in CodePipeline for DevSecOps teams to implement application scanning. This pipeline in particular uses:

1. truffleHog - Searches through git repositories for secrets, digging deep into commit history and branches. This is effective at finding secrets accidentally committed.
2. OWASP Dependency Checker - Dependency-Check is a Software Composition Analysis (SCA) tool that attempts to detect publicly disclosed vulnerabilities contained within a project’s dependencies.

The public key in this repository is a test object to trigger a failed build through truffleHog.