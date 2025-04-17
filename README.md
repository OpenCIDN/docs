# Quick Start

This guide will show you how to set up and run the OpenCIDN service using Docker Compose.

The OpenCIDN system consists of 5 components:

- **Gateway**: This is the main entrance of the project.
- **Auth**: Add user management and access control for the **Gateway**.
- **Agent**: Add the cache backend extension to the **Gateway**.
- **Queue**: This is the sync tasks queue for the **Gateway** and the **Agent**.
- **Runner**: This is processing sycn tasks for the **Queue**.

Here is a demo of the available deployment configurations:

- [Basic Gateway](./examples/basic/): Core functionality.
- [Gateway with Authentication](./examples/auth/): Adds a user management and access control.
- [Gateway with Caching](./examples/cache/): Adds a caching layer to improve performance.
- [Sync Queue & Runner](./examples/queue/): Enables efficient source-to-cache synchronization.
- [Extend Agents for Gateway](./examples/agents/): It balances the workload across multiple cache backends.
