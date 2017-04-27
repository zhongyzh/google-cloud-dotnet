This (orphan) branch contains the docfx metadata (and any other
useful artifacts) from the external dependencies to the code in this
repo. This allows documentation to be generated quickly without
having to clone multiple repositories, regenerate metadata using
several different versions of the .NET Core SDK etc.

The contents can be regenerated using the fetchdependencies.sh
script under the docs directory of the master branch.
