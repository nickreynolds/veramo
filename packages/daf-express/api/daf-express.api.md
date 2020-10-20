## API Report File for "daf-express"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { IAgent } from 'daf-core';
import { Request as Request_2 } from 'express';
import { Router } from 'express';

// @public
export const AgentRouter: (options: AgentRouterOptions) => Router;

// @public (undocumented)
export interface AgentRouterOptions {
    basePath: string;
    exposedMethods: Array<string>;
    getAgentForRequest: (req: Request_2) => Promise<IAgent>;
    serveSchema?: boolean;
}


```