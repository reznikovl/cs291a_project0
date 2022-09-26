# cs291a_project0

| Concurrency Number      | Requests in 10 seconds |
| ----------- | ----------- |
| 1      | 188       |
| 2   | 411        |
| 4      | 847       |
| 8      | 1731       |
| 16      | 2962       |
| 32      | 3858       |
| 64      | 4355       |
| 128      | 4745       |
| 256      | 4536       |

- There are diminished returns because the server does not have unlimited bandwidth to handle so many requests coming in at the same time. Increasing from 1 to 2 doubled it, because the server was able to process all the data as it comes in. On the higher end, though, the numbers even decreased. This is likely because the server is at or near the capacity of requests it can handle simultaneously, and is getting overwhelmed. 
- For example.com (as per the Piazza answer), requesting with http yielded 625 requests in 10 seconds and http yielded 204. This makes sense, as this means that the extra effort needed to encrypt the traffic has significant performance implications.
- Github developers have likely spent a lot of time, energy, and money on making their website responsive. They do this by buying more servers, for faster computations. It's also possible that they have many servers distributed around the world, and therefore is able to offer less latency and more concurrent capabilities by redirecting traffic to the server closest to the user.
- My site's "Time to Interactive" speed is 0.2 seconds.
