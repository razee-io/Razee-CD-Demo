# Configuration files

Configuration is organized by cluster type: `dev`, `preprod`, and `prod`.
Each configuration list contains:

  - A duplicate of the bootstrap resources to enforce, that can also be updated with a new version of config.
  - A remote resource that installs all the microservices for this cluster type.


# LaunchDarkly

- Create flags in the default LaunchDarkly environment for each microservice.
- Add a variants for each.
- Create rules for each type (`dev`, `preprod`, `prod`), choosing an advertised version for each.
