# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js servers: unresponsiveness due to long-running operations blocking the event loop.  The `server.js` file contains code that simulates this problem. The `serverSolution.js` file shows how to resolve the issue using asynchronous programming.

## Problem

The main issue is blocking the event loop. The `while` loop prevents the server from responding to other requests.