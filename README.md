This is a copy-and-paste clone of the react-scripts package.

This is necessary to fork since the upstream package has stopped updating its
dependencies and apparently is unmaintained now. More specifically, react-scripts
declares a dependency on Typescript < 5.0, but since Typescript doesn't use
semantic version numbers this dependency is meaningless and pointlessly prevents
you from using a more recent version of Typescript.

We have to clone via copy and paste rather than using a fork since the upstream
is a monorepo and I don't want to copy all that.
