# workflow
generic reusable workflow

this is a generic, reusable github workflow that aims to address around 80% of modern application deployment use cases.

there are cetrain decisions made in the spirit of following best practies that have been listed below.

Feel free to reuse as needed

Decision: an environment is required in order to accomplish anything
Reason: As we are able to put many checks and balances in place around our environments in GitHub, this reusualbe workflow requires then in order to prevent malicious or accidental deployments to environments (like prod) without explicit deployment.