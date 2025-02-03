#### Learnings

**[db.ts](./lib/db.ts)**

- next.js runs on edge servers so to avoid multiple db connections on each different edge - its important to implement caching to avoid multiple connections during the application's lifecycle.
