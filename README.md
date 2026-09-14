# gha-assoc-probe

A calibration repository. It measures which `author_association` value GitHub
assigns to the author of a pull request, as a function of that author's prior
relationship to this repository (no commits / one merged commit / collaborator).

Nothing here is specific to any other project. The workflow only echoes fields
of the event payload.
