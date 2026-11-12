# configurations
 


## Local stack configuration

Each stack keeps its private values in a local `.env` next to its Compose file.
The `.env.example` files document variable names without credentials. If `.env` does not
already exist, copy the example and fill the required values before using that stack.
Existing private values were preserved locally when these configurations were versioned.

These files preserve historical configurations. Committing them does not deploy a stack;
check image versions, volumes and host-specific paths before running Docker Compose.
